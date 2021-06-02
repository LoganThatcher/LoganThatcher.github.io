---
title: Robo Revolution
layout: template
filename: RoboRevolution.md
---

# Overview

  The game is played with two players who take turns moving their units and trying to shoot the other team. 
  The turn starts with an overhead view of the battlefield, where the current team's player can select one of their units. 
  Once selected, the player takes control of the unit and has 15 seconds to move and take a shot with their weapon. 
  If the player runs out of time or shoots their weapon, the turn will change to the next player. A player must cycle through all 
  of their units before a previously used one will be available again. We made this decision so players would be forced to use all of their units. 
  Once a player has defeated all of the enemy team's units, the player wins.

## Development

  The game was developed by a team of 4 students. It was written in C++ with direct calls to the OpenGL API. 

## General Pictures

![Image of Map and Editor](https://loganthatcher.com/images/RoboRev/mapEditorAndOverhead.png)

  Our map editor allowed a pixel map (as seen in the lower half) to be imported to the game. The map editor would process the image and turn it into
  a result like the map seen in the top half of the image.

![Image of Startup](https://loganthatcher.com/images/RoboRev/startup.png)
  Players are presented with instructions upon starting the game.

![Gif of Camera Zoom](https://loganthatcher.com/images/RoboRev/camera_zoom.gif)
  Camera zoom when selecting a character
