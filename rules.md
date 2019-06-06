#title:Pipe Land - Rules
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

.diagram {
    max-width:75%;
}
"

Overview
--------

In this game players take turns to place, purchase and rotate Land Tiles, in order to get water to as many of their Land Tiles as possible.

At the end of each turn, players recieve money for each irrigated Land Tile they own, and normally the first player to successfully irrigate 10 Land Tiles or make £50 wins. 

Equipment
---------

* 1 River Tile
* 114 Land tiles.
    - 12 for each of the 6 player colours with different pipe shapes on.
        * "T"s , Corners, Straights, Pluses, and Double Corners.
    - 38 grey tiles: as above, but unowned. 
* Coloured Counters
* Game Currency, able to represent amounts from £0 to £50 for each player. 

These rules will use the '£' symbol to represent Currency.


Key Terms 
---------

**Land Tile:** Every tile is considered a piece of Land.  The colour of that Land shows who owns it.

**State Tile:** Some Land Tiles are Grey and have a shield on them, this means that they are owned by the state, and not by any player. They can however be bought for a set price. Once a player has paid for a Land Tile, they mark ownership by placing a counter of their colour over the shield.

**Tap Tile:** A Land Tile with the word "Tap" on the back, these are all 'T' shaped and are always placed touching a **River Pipe**.

**Pipe:** Every tile has a pipe across it, if the pipes connect, then water flows freely across, and can be used to **Irrigate** that Land.

**River Pipe:** The two or three pipes that reach across the River. These contain the pumps and act as the source of water.

**Irrigate:** If a Land tile you own has a complete path from one of the River Pipes to it, then it is considered Irrigated. At  the end of each turn you receive £1 for it.

**Bank:** The holder of all spare game money. 


Setting Up the Game
--------------------

### Sort the tile Cards:

Each player chooses a colour, from the available Land Tiles. Remove all other coloured Land Tiles, keeping only the State Tiles, and those of the chosen colours.

Separate the cards into groups by their backs (Tap, 1, 2, 3, 4). Shuffle them separately and place each pile, face down, beside the main play area.

### Set up the River:

The River tile is 2 sided, one side has 2 pipes across it, the other has 3.

Place the River Tile in the middle of the playing area showing 2 pipes for 2-4 players, or 3 pipes for 5-6 players.

Place a Tap Tile tile of each playing colour against each of the pipes out from it. In any leftover Pipe spaces, place an State Tap Tile.

All of these Tap Tiles are 'T' shaped, and the bottom of the 'T' should be touching the River Pipe.

<img class="diagram" src="{{join (cfg "rel") "small_layout.svg"}}">

*In the Above image there are 3 players, and the 4th pipe is covered by an unowned Tile*

Then place all of the '1' Tiles randomly around them. This is best done, by placing them all face down, and then flipping them.

    Note: In the Advanced/Intended game-play, Players negotiate over the placement of each of these tiles. See "Advanced Play".   
    However until you have played the rest of the game it's hard to know what you are aiming for.

Depending on the number of players you will have a different number of cards, so rather than say exactly how to lay them out, here are some guidelines.

The layout:

* Symmetrical, in both directions if possible.
* If Symmetry is not possible then make the State Tiles the odd one out.
* Not wider than the river.
* Not deeper than it needs to be. 

Tiles:

* Any orientation 
* Tap Tiles should be surrounded.

<img class="diagram" src="{{join (cfg "rel") "random_layout.svg"}}">

*Eg: With 3 Players there are fifteen '1' cards so perfect symetry is not possible. As such, the State Tile is the odd one out and has one fewer cards around it.*


### Starting Money:

Decide randomly who will go first. Give that player £5, then to the next player £6, then £1 more to each player around the table as compensation for starting later.

If there are only 2 players, the second player starts with £7

How to play
-----------

### Turn Overview

Players take turns clockwise around the table to do each of the following:

* First: Place a Land Tile
* Second: Perform any number of Actions they can afford (in any order).
    - Rotate a Land Tile
    - Buy a Land Tile
* Finally: Receive Money for all Land Tiles they own that are irrigated.

If a player performs more than one action in a single turn, there is an extra Tax applied. See **Multiple Action Tax** below.

### Place a Land Tile

Draw a tile from the lowest numbered available Pile, and place it on the board according to the following rules. 

1. You *must* place the tile adjacent to a Land Tile already on the board.
2. You *must* place the tile, such that it is possible to connect to the River by rotating only the tiles currently on the board. However it does not have to be connected right now.
3. You *may* choose the orientation.
4. You *may not* place an Owned (Coloured) Land Tile next to another Land Tile of the same colour.
5. Other players *may* offer you money to place it where they want.
6. You *may* solicit offers.

    Hint: Leave a small space between the tiles. This will make it easier to rotate them when needed.

<img class="diagram" src="{{join (cfg "rel") "can_explore.svg"}}">

* A: Yes: Rotating a few tiles will enable that location to be reached"
* B: Yes: Currently connected
* C: No: No amount of Rotating Tiles will Connect that space. It Once more tiles have been played it may become reachable.
* D: No: You cannot place a tile next to a tile of the same Color.

<pre><code>Note: Do not actually rotate any other tiles, only check that it is possible. Rotation only happens as an Action.</code></pre>

### Action - Rotate a Land Tile

Select a Land Tile and Rotate it to any of the four orientations you choose.

* If you own it, this is Free.
* If another player owns it, you must pay them what they ask.
* If it is a State Tile, you must pay the bank £3.

You may also accept payment to rotate a tile for someone elses benefit.

### Action - Buy a Land Tile.

To buy a Land Tile, you must pay its price and then place a counter of your colour on it to show it is now yours.

If you wish to buy land from another player, you must agree on a price.

If you wish to buy a State Tile, you must pay the Bank the set price based on the Tile's physical distance from the nearest River Pipe. (As the Rook flies) 

You may not buy the tile you placed this turn.

Each State tile costs £14 minus £2 for every step between them and the nearest River Pipe. Down to a minumum cost of £4.

    Clarification: So the Tap Land Tiles cost £14, and all tiles next to them cost £12.


<img class="diagram" src="{{join (cfg "rel") "rook_flies.svg"}}">

*The above diagram shows that the distance ignores whether or not tiles are in the path. The highlighted £8\* cost is counted in steps along the red arrows. *


### Multiple Action Tax

In order to perform more than one action in a turn a player must pay a Multiple Action Tax to the Bank. This is on top of whatever costs they incur performing the action.

    Note: Placing a Land Tile does not count as an action.

The Tax per Action increases by £1 with each extra action starting at a cost of £2 for the second action.

    Example: Alice Rotates her own Land tile for free, then purchases a State Tile for £8, finally Alice pays Bob £4 to Rotate one of his tiles.
    
    To perform these 3 actions, Alice must also pay a Multi Action Tax of £2 + £3 = £5 

    Her Total cost is therefor £17. That is £13 to the bank, and £4 to Bob.

You may not perform an action if you cannot pay the tax.

### Earn Money

At the end of a players turn, for each Irrigated Land Tile they own, they receive £1 from the bank.

An Irrigated Land Tile is any Tile from which you can find a pipe path back to the River. This path can be through other players' land.

Ending the Game
---------------

### Victory Conditions

At the end of any player's turn, if they have successfully done either of the following, they win, and the game ends immediately.

* Irrigated 10 Land Tiles that they own
* Collected at least £50

### No more Tiles

If no player has already won when the last Land Tile is placed, then, after that turn, each player gets one final turn. 

In this turn they do not "Place a Land Tile", and after taking their actions, they receive double money for their irrigated Land Tiles.

After this the game ends and the player with the most money wins.

Withdrawing
--------------

Withdrawing allows players to leave the game without disrupting play for the others. Either as a resignation or because of external circumstances.

A player may choose to Pass their turn, by not "Placing a Land Tile" and not performing any Action.

    Note: If you place a Land Tile, but perform no other action, this is not considered passing.

The first time a player Passes they are still considered in the game, and so they still receive income, and other players must negotiate with them to act on their Land.

After a player passes for the second consecutive time, they are considered withdrawn from the game.

* They do not receive income at the end of their turn.    
* Other players may buy from them, and rotate their Land, at the same price as Unowned Land.

A player may return to the game, by taking their turn again in the normal order of play. As soon as they do this, they may collect income, and negotiate as before.

If only one player remains in the game, they win.

Advanced Game
------------

    Note: this is the intended way to play, but makes more sense after all players have tried the Basic game.

Here are the differences to the basic game

* Do not place the 1 Tiles randomly. Instead leave them in their own pile.
* Each player starts with £5
* Until all players have 4 Tiles on the board (including the Tap), players may only Place a Land Tile, and may not perform any Actions or receive income. 
* Players may negotiate around the placement of any tile even the '1's.
* The player who places the last player's 4th Tile may Take Actions and recieve Income.
* When this happens, all other players immediately receive the compensation money:  £1 , £2 ,£3 ... around the table.
