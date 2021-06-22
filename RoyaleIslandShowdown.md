---
title: Royale Island Showdown
layout: template
filename: RoyaleIslandShowdown.md
---

# Project Summary

Royale Island Showdown is an online multiplayer shooter. It contains battle royale elements where 4 players will dive down on the island map, 
collect resources, and try to be the last player standing.  Each player has an AI teammate that works with them to win.

### Development

The game was built in Unreal Engine 4, by myself. It uses a combination of C++ and Unreal Blueprints.

And the game is available on Steam. [Link to the steam store page](https://store.steampowered.com/app/1528570/Royale_Island_Showdown/)

## Map overview

![Image of Map Overview](https://loganthatcher.com/images/RIS/images/Overview16by9.png)

The game map has a variety of features and sections, with 1000+ trees, boxes, walls, barrels and buildings.

## The Teams

![Image of Map Overview](https://loganthatcher.com/images/RIS/images/TeamShot.png)

There are 4 teams each consisting of one player and one AI, denoted by their color. 

## Locations Across the Map

![Composite Image of Across the Map](https://loganthatcher.com/images/RIS/images/RIS_Map_Composite.png)

This composite shows 4 locations from different areas of the map, each from the player's viewpoint

## Starting the Match

![GIF of Plane Flight](https://loganthatcher.com/images/RIS/GIFs/PlaneFlight.gif)

All players begin by flying over the island in a plane

![GIF of Falling](https://loganthatcher.com/images/RIS/GIFs/Falling.gif)

When they choose, players can jump out and fall to the island where they want

## Moving Around the Map

![GIF of Walking All](https://loganthatcher.com/images/RIS/GIFs/WalkingAll.gif)

Players then move around the map collecting gear




![GIF of AI Teammate All](https://loganthatcher.com/images/RIS/GIFs/AITeammateAll.gif)

The AI moves and collects gear independently while staying near the player and trying to predict their plan.



## Collect Resources

![GIF of Collecting Resources](https://loganthatcher.com/images/RIS/GIFs/CollectResources.gif)

There are three types of resources for the players: guns, health, and ammo



## Shooting

![GIF of Shooting](https://loganthatcher.com/images/RIS/GIFs/Shooting.gif)

There are three types of weapons, each with sound and muzzles flash when shooting

## Fighting Enemies

![Image of Mini Map](https://loganthatcher.com/images/RIS/images/MiniMap.png)

There is a minimap in the top left corner of the screen which player's can use to find enemies
(not always pictured since some images are from earlier in development)



![Image of Fighting Enemies](https://loganthatcher.com/images/RIS/images/FightingEnemies.png)

The red player on the left is reloading while his teammate is shooting at the blue team.

![GIF of Fight](https://loganthatcher.com/images/RIS/GIFs/Fight.gif)

In this fight, at the beginning the red AI recognizes that the red player is going after the Blue team and runs to lead the way. 
The blue AI runs for cover behind the tree but once his blue player backs off, he turns to join him.


## Additional Technical Effects 

![Image of Border Wall](https://loganthatcher.com/images/RIS/images/BorderWall.png)

There is a border wall that periodically shrinks to restrict play space to maintain pacing and encourages players to interact.

![Image of Low Health](https://loganthatcher.com/images/RIS/images/LowHealth.png)

Low health is indicated to the player by light blurring as well as red tinting and vignette. 
These effects become more pronounced as health drops.

![Image of Underwater](https://loganthatcher.com/images/RIS/images/Underwater.png)

When players are underwater, they slowly lose health. While underwater there is a blue tinting and strong vignette.

