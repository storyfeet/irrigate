#title:Irrigate - Rules
#css:"
th, td{
    border:1px solid black;
    padding:4px;
    //text-align:right;

}
span {
    font-family:Monospace;
}
pre {
    background:#dddddd;
    padding:5px; 
    white-space:pre-wrap;
}
img {
    max-width:90%;
}
"


Equipment
---------

* 1 River Tile
* 90 Land tiles.
    - 10 for each of the 4 player colours
        * 4 "T"s
        * 3 Corners
        * 3 Straights
    - 44 grey tiles as above, but unowned. 
    - 4 grey (unowned) Goal-Tiles 
* Coloured Counters
* Game Currency, able to represent amounts from 0 to 50 for each player

Aim
---

To win the game you must do one of the following.

* Irrigate 10 Land Tiles you own.
* Irrigate 1 Goal Tile you own.
* Make 50 Currency

Key Terms 
---------

**Land Tile:** Every tile is considered a piece of Land.  The colour of that Land shows who own's it. If someone buys that Land, they place a coloured counter on it to show it is now theirs.

**Unowned Tile:** Some Land Tiles are Grey, this means that they are not owned by any player, but can be bought for a set price. This is shown by placing a coloured counter on the Tile.

**Goal Tile:** A tile, which has a large circle in it. These Lands are valuable, and if you purchase and irrigate just one of these, you win the game. All these tiles say Goal on the back.

**Pipe:** Every tile has a pipe across it, if the pipes connect, then water flows freely across, and can be used to **Irrigate** that Land.

**River Pipe:** The two pipes that reach across the River. These contain the pumps and act as the source of water.

**Irrigate:** If a Land tile you own has a complete path from one of the River Pipes to it, then it is considered Irrigated. At  the end of each turn you receive one Money for it.

**Bank:** The owner of all Land not owned by any other player, and holder of all spare game money.


Setup
-----

### Sort the tile Cards:

Each player chooses a colour, from the available Land Tiles. If there are colours left, then remove all tiles of those colours from the game, keeping only the grey Land Tiles, and those of the chosen colours.

Separate the cards into groups by their backs (Tap, 1, 2, 3, 4), and shuffle them.

### Set up the River:

Place the River Tile in the middle of the playing area, and place a "Tap" tile of each playing colour against each of the pipes out from it. In any leftover Pipe spaces, place an Unowned Gray "Tap" Tile.

All of these Tap Tiles are 'T' shaped and the bottom of the 'T' should be touching the River Pipe.

<img src="{{join (cfg "rel") "small_layout.svg"}}">

*In the Above image there are 3 players, and the 4th pipe is covered by an unowned Tile*

### Starting Money:

Give each player 5 money.


How to play
-----------

### Early Game

Players take turns clockwise around the table to **Place a Land Tile** from the '1' Pile until all players have 4 Tiles of their colour on the board.

**Placing a Land Tile**

Draw a tile from the lowest numbered available Pile, and place it adjacent to a tile already on the board.

* You *must* place the tile, such that it is possible to connect to the River by rotating only the tiles currently on the board. However it does not have to be connected right now.
* You *may* not place an Owned (Coloured) Land Tile next to another Land Tile of the same colour.
* You *may* negotiate money from another player to help help you decide where to place it.

If the tile is a "Goal Tile" it must be placed diagonally from any other tile on the board. 

    Note: This won't happen in the Early Game, but is part of placing a tile


**Ending the Early Game**

On the turn that a player places the last players 4th Tile. That player will be able to play a complete turn.

As compensation, each player around the table clockwise from that player, recieves one more money than the last. 

Or -- in a two player game, the other player recieves 2 extra money.

Now move to the **Main Game**.

### Main Game

Players take turns clockwise around the table to do each of the following:

* First: Place a Land Tile (As above)
* Second: Perform any number of actions they can afford (in any order).
    - Buy Land
    - Rotate Land 
* Finally: Recieve Money for all Land Tiles they own that are irrigated.

If a player performs more than one action in a single turn, there is an extra Tax applied. See **Multiple Action Tax** below.


### Action - Rotate a Land Tile

If you own the land tile, you may rotate it to any of the four directions you choose. You may also accept payment from other players to do this to their benefit.

If you do not own the land, then you must pay the owner for permission to rotate it.  If the owner is another player then you must agree on a price.

If the owner is the Bank, then you must pay the Bank 3 money.

### Action - Buy a Land Tile.

If you wish to buy land from another player, you must agree on a price.

If you wish to buy land from the Bank, the prices are as follows.

<table>
    <tr><th>Group</th><th>Cost</th></tr>
    <tr><td>River</td><td>14</td></tr>
    <tr><td>1</td><td>12</td></tr>
    <tr><td>2</td><td>10</td></tr>
    <tr><td>3</td><td>8</td></tr>
    <tr><td>4</td><td>6</td></tr>
    <tr><td>Goal</td><td>25</td></tr>
</table>

Once you have paid the required amount of money, place a counter of your colour on the Land Tile you have bought. This tile is now yours. 

### Multiple Action Tax

If a player wishes to perform more than one action in a single turn, they must pay a tax to the bank. This is on top of whatever costs they incur performing the action.

The Tax per Action increases by 1 with each extra action starting at a cost of 2 money for the second action.

The table below shows the total Tax for performing a number of actions in a single turn.

<table>
<tr><th>Action #</th><th>Tax for Action</th><th>Total Tax So Far</th></tr>
<tr><td>1</td><td>--</td><td>--</td></tr>
<tr><td>2</td><td>2</td><td>2</td></tr>
<tr><td>3</td><td>3</td><td>5</td></tr>
<tr><td>4</td><td>4</td><td>9</td></tr>
<tr><td>5</td><td>5</td><td>14</td></tr>
<tr><td>...</td><td>...</td><td>...</td></tr>
</table>

You may not perform an action if you cannot pay the tax.

### Earn Money

Once a player has completed all the actions they wish to, they earn money for each Irrigated Land Tile they own. 

An Irrigated Land Tile is any Tile from which you can find a pipe path back to the River. This path can be through other players land.

For each Irrigated Land Tile the player owns, they receive 1 money from the bank.

Once they have done this their turn is over.


### Withdrawing

Withdrawing allows players to leave the game without disrupting play for the others. Either as a resignation or because of external circumstances.

A player may choose to Pass their turn, by not exploring and not performing any Action.

The first time a player passes they are still considered in the game, and so they still receive income, and other players must negotiate with them to act on their Land.

After a player passes for the second consecutive time, they are considered withdrawn from the game.

    * They do not receive income at the end of their turn.    
    * Other players may buy from them, and rotate their Land, as though they are the bank.

A player may return to the game, by taking their turn again in the normal order of play. As soon as they do this, they may collect income, and negotiate as before.

If only one player remains in the game, they win. This win is as valid as any other.

Ending the Game
---------------

At the end of any players turn, if they have successfully done any of the following they win the game immediately.

* Irrigated 10 Land Tiles that they own.
* Bought and Irrigated 1 End Tile.
* Collected at least 50 money

