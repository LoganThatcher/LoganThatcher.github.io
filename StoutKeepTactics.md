---
title: StoutKeep Tactics
layout: template
filename: StoutKeepTactics.md
---

# Project Summary

This is a two player digital board game. Players take turns spawning in new units, moving them, attacking, 
and capturing flags. Players score a point for each flag they have control of at the start of their turn. 
The first player to reach 30 points wins. 

### Development

This game was built by a team of 3 people in Unity. I was responsible for the game design and refined it 
through design iteration. I ran a series of user tests to understand the different 
perspectives, playstyles, and approaches
of players to the game. For this game, I also created the pixel art units and coded the movement of them.


## Pictures From The Game

![Image of Board](https://loganthatcher.com/images/SKT/Board.png)

This is the starting configuration of the board with each player having 3 units. The six capture flags start white 
(neutral) and change to the team's color when a unit is placed on them.

During a player's turn, they have a limited number of actions (represented by AP on the top bar).
Summoning units takes 1 to 4 AP depending on the unit type (mage, swordsman, archer, or cavalry).
The player clicks one of the bottom buttons to deploy a new unit 
and can then place it on any unoccupied space in the first 3 columns on their side.
 
<br>

![Image of MovementUI](https://loganthatcher.com/images/SKT/MovementUIBig.jpg)

Moving and attacking take 1 AP each.
Each unit type can move a different number of squares, has different attack ranges, and 
deals a different amount of damage.

When selecting a unit, the squares it can move to are colored blue and the squares it could attack 
from the new location are colored red.
Each unit can only move and attack once per turn. 

<br>

![Image of All Units](https://loganthatcher.com/images/SKT/AllUnits.png)

These are the four pixel art sprites that I made for the different types of units.

![Image of Units from the two teams](https://loganthatcher.com/images/SKT/BothArchers.png)

There are color variants of each unit for the two teams that are mirror images based on the direction of play.
