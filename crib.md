#css:"
h2{
    font-size:medium;
    margin-top:0;
}
.hello{
    display:flex;
    flex-wrap:wrap;
    border:1px solid blue;
}
.hello ul{
    font-size:small;
}
"

{{define "Poop"}} 
<ul>
<h2>On Your Turn</h2>
<li>Explore a Land Tile</li>
<li>Take any number of actions</li>
<li>Receive Income</li>
</ul>

<ul>
<h2>Winning the Game</h2>
<li>Own and Irrigate 10 Land Tiles</li>
<li>Own and Irrigate 1 Goal Tile</li>
<li>Earn £50</li>
</ul>

<ul>
<h2>Actions</h2>
<li>Rotate a Land Tile:</li>
    <ul>
        <li>Yours: Free</li>
        <li>Unowned: £3</li>
        <li>Someone Else's:Negotiate</li>
    </ul>
<li>Buy a Land Tile:</li>
    <ul>
        <li>Unowned: £14 - distance x £2</li>
        <li>Someone Else's:Negotiate</li>
    </ul>
</ul>

<ul>
<h2>Multi Action Tax</h2>
    <li>First Action: £0</li>
    <li>Second Action: + £2</li>
    <li>Third Action: + £3 </li>
    <li>Fourth Action: + £4 </li>
    <li>...</li>
</ul>

{{end}}
{{range $k,$v := seq 3 }} 
<div class="hello" > {{template "Poop"}} </div>
{{end}}


