---
title: Robo Revolution
layout: template
filename: RoboRevolution.md
---

# Project Summary

Robo Revolution is a 1v1 game that mixes turned based strategy with first person shooter controls.
Players take turns moving their units and trying to shoot the other team.
The turn starts with an overhead view of the battlefield from which the player selects a unit. 
They have a limited time to move and their turn ends when they shoot or run out of time.
Once a player has defeated all of the enemy team's units they win.


### Development

This game was developed C++ with direct calls to the OpenGL API by a team of 4 students. 
I implemented the graphical optimizations View Frustum Culling and Back Face Culling. I also built 
visual debuggers to verify the functionality and performance of these optimizations. I used multipass
rendering techniques to add shadows to the game world and apply motion blur to particular scenes. 
I designed the game map and wrote a map editor that took in a pixel map image to generate the game board. 
   

## Overview

![Image of Map and Editor](https://loganthatcher.com/images/RoboRev/mapEditorAndOverhead.png)

  The map editor allows a pixel map (shown in the lower half of the image above) to be imported to the game.
  It processes the image and turns it into the result seen in the top half of the image above.


## Tutorial

![Image of Startup](https://loganthatcher.com/images/RoboRev/startup.png)

  Players are presented with instructions upon starting the game.


## Gameplay

![Gif of Camera Zoom](https://loganthatcher.com/images/RoboRev/cameraZoom.gif)

  From the overhead view the player selects then possesses a unit.

  <br>

![Gif of Collecting a health powerup and shooting](https://loganthatcher.com/images/RoboRev/healthPowerupAndShooting2.gif)

  This is an example of a turn. The player collects a health pickup before shooting an enemy.
  <br>

![Gif of Shotgun shot and unit death](https://loganthatcher.com/images/RoboRev/ShotgunShotAndUnitDeath.gif)

  The player uses the shotgun pickup to kill an enemy unit.
  <br>

![Image of Player 1 winning](https://loganthatcher.com/images/RoboRev/player1win.png)

  This is the victory screen shown when player 1 wins.


## Pickups

![Gif of Picking up a Shotgun](https://loganthatcher.com/images/RoboRev/PickingUpShotgun.gif)

  Two shotguns ware located on the map. Moving over one gives it to that unit.
  <br>

![Image of Health Powerup](https://loganthatcher.com/images/RoboRev/healthpowerup.png)

  Four health pickups are located on the map. Walking into one restores a health to the unit.
  <br>


## Technical Effects

![Gif of Environmental Mapping and Skybox](https://loganthatcher.com/images/RoboRev/EnvironmentalMappingAndSkybox.gif)

  Reflections of the skybox can be seen in the map textures through the use of environmental mapping.
  <br>

![Image of Death Boom](https://loganthatcher.com/images/RoboRev/deathBoom.png)

  Animated particles fly out from units when they die.

![Image of Bullet Camera with Blur](https://loganthatcher.com/images/RoboRev/bulletCameraWithBlur.png)

  Motion blur is activated when the bullet camera is on.


