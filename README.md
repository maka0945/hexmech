# HexMech

## Project Members

| Name               | Github                                             |
|:------------------ |:-------------------------------------------------- |
| Matthew Kaplan     | [@maka0945](https://github.com/maka0945)           |
| Max Lookabaugh     | [@MaxLookabaugh](https://github.com/MaxLookabaugh) |
| Michael R. Shannon | [@mrshannon](https://github.com/mrshannon)         |
| Mack Colwell       | [@MColwell](https://github.com/MColwell)           |


## Description
BattleTech is a turn-based strategy board game in which players command 1 or
more BattleMechs (mechanized suits of armor represented by figurines) in
combat on a game board.  We hope to create an online version of the game in
which users can play against each other and enjoy all of the same features as
the introductory rules to the board game.


## Vision Statement

> Crushing metal with every commit.


## Motivation
BattleTech is currently played in person with charts, sheets, and very many
dice rolls, or it is played using the MegaMek application.  Playing in person
is difficult because fans of BattleTech are not always located in clusters.
Furthermore, playing BattleTech by hand can be very tedious, especially for
new players who don't know all the rules.  The other option is the MegaMek
application which is Java based and suffers from an overly complicated
interface using multiple windows.  The intention of HexMech is to make
BattleTech more accessible by:
* Using a browser only client requiring no installation.
* Hiding the complexities of the math behind a game of BattleTech.
* Informing players of the rules only when they try to break them.
* Increasing the speed of the game and also allowing correspondence style games
  which will reduce time commitment to play.
* Providing an easy to install server.
* And finally, establishing a platform that could allow a community of players
  to assemble and play in a unified location and possibly be expanded in the
  future to an in game economy/persistent universe.


## Risks
* JavaScript (both client side and node.js) are relatively new to all members
  of the team.
* Most of the team has never written a game before.
* The team has never worked together before.
* We have few times that everyone is free each week.
* BattleTech is relatively new to all of our members.
* We don't have any experience with rendering graphics in HTML5.
* The hex grid required by BattleTech poses some difficulty in storage and
  calculations.
* Not completing an entire set of rules.

### Mitigation
* A running start with the rules of BattleTech is helping with understanding
  the features needed.  Also, one of our members knows many fans of BattleTech
  who can answer questions related to the game rules themselves.
* Using industry standard libraries such as jQuery, ExpressJS, socket.io, and
  possibly pixi.js should make the transition to JavaScript easier.
* The article at [Hexegon Grids](http://www.redblobgames.com/grids/hexagons)
  should provide ample documentation on how to store and perform calculations on
  hex grids.
* There are many rules we can cut out for time if we need to and still have
  a functional product.  This is one of the main reasons we have chosen the
  Agile project methodology.
* We do have some experience in graphics design and programming.


## Requirements

| Requirements |
|:------------ |
| As a player, I want to pick a Mech so I can play a game. |
| As a player, I want to invite other player to join my game so I can crush them. |
| As a player, I want to setup a game so I can play. |
| As a player, I want to select a map to play on. |
| As a player, I want a leaderboard for bragging wrights. |
| As a player, I want to sign up for an account so my game history can be saved. |
| As a lonely player, I want to get matched with other players so I can play without friends. |
| As a player, I want to shoot other Mechs so I can kill them. |
| As a player, I want to move my Mech so I can get within range of other Mechs. |
| As a player, I want to pound other Mechs with powerful melee attacks. |
| As a developer, I want a working sever so I can serve the game and write the backend. |
| As a player, I want to fancy graphics to hold my interest. |
| As a player, I want explosions so I can feel like a cool person. |
| As a developer, I want a cool 404 page so I can show it off. |
| As a player, I want tooltips that teach me how to play so I can learn without reading a rulebook. |
| As a player, I want to know if my opponent is AFKing or not so I don't waste my time. |
| As a player, I want terrain so I can hide behind it. |
| As a player, I want the initiative phase to decide who goes first so I a turn can start. |
| As a player, I want to be able to have my Mech walk, run, or jump. |
| As a player, I want to be able to change the direction my Mech is facing. |
| As a player, I want to have the falling rules to make the game more challenging. |
| As a player, I want to make my Mech go prone so I can hide from enemies. |
| As a player, I want to be able to stand my Mech up after falling. |
| As a player, I want my MechWarrior to be able to take damage to make the game more interesting. |
| As a player, I want the piloting skill role system from BattleTech so I can avoid falling. |
| As a player I want a line of sight calculator so I can tell if I will be able to aim at my target. |
| As a player, I want terrain to interfere with line of sight to make the game more interesting. |
| As a player, I want to be able to torso twist my Mech so I can shoot other Mechs to the side of mine. |
| As a developer, I want a library I can use to deal with indexing, distance calculation, and line of sight calculation on a hex grid so I can write the game logic. |
| As a player, I want to be able to aim my weapons individually so I can hit more than one target. |
| As a player, I want the BattleTech heat system so I have a reason not to fire all my weapons. |
| As a player, I want armor to take damage when hit so I can hit the internal structure. |
| As a player, I want internal structure damage so I can destroy the enemy. |
| As a player I want the critical damage system so I destroy my enemies weapons and equipment. |
| As a player, I want to be able to have my Mech punch another Mech to do more damage. |
| As a player, I want to be able to have my Mech kick another Mech to do more damage. |
| As a player, I want to perform a Death from Above attach so I can deal damage while looking cool. |
| As a player, I want the push mechanic so I can push my enemy off of a cliff. |




User & Functional Requirements:  
As a player, I want to pick a mech so I can play a game.  
As a player, I want to invite other players to join my game so I can crush them.  
As a player, I want to setup a game so I can play.  
As a player I want to name my mech so I can remember it.  
As a player I want a leaderboard so I can show off to my friends.  
As a player I want to sign up for an account so I can save my win history.  
As a lonely player I want to get matched with other players so I can play without friends.  
As a player I want to move my mech around so my mech will be close enough to attack the enemy.  
As a player I want to shoot other players so I can kill them.  
As a player I want to curb stomp other players so I can kill them harder.  
As a player I want pretty pictures on the screen so I can enjoy them.  
As a player I want to see explosions so I can feel like a cool person.  
As a developer I want a cool 404 page so I can show it off.  
As a developer I want the code to be well commented so it is easy to maintain.  
As a player I want all the rules so I know how to play.  
As a player I want terrain so I can know where I am.  
As a player, I want to know if my opponent closed the page so I can do something else instead of waiting for them to take their turn.
As a player, I want to quit the game so I can start a new one after.

Non-functional Requirements:  
Relay game state to everyone within 1 second.
Don't crash.


## Methodology

We will be using the Agile methodology when applicable and only dipping into
a Waterfall like approach when a common design must be established between the
back and front ends.


## Project Tracking Software
* Our team will be using Trello as our Project Tracking Software.
* Link:
  * https://trello.com/b/WtyVbDpn/hexmech

## Project Plan
