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

![Image of Shotgun Pickup](https://loganthatcher.com/images/RoboRev/shotgunpickup.png)

  Two shotguns were located on the map. Moving over them will give players the ability to use them.

![Image of Health Powerup](https://loganthatcher.com/images/RoboRev/healthpowerup.png)

  Four health pickups are located on the map. Interacting with a pickup will restore one health to the unit.

![Image of Player 1 winning](https://loganthatcher.com/images/RoboRev/player1win.png)

  The victory screen for player 1

![Image of Environmental Mapping](https://loganthatcher.com/images/RoboRev/environmentalMapping.png)

  Reflections of the skybox can be seen in the map textures through the use of environmental mapping.

![Image of Death Boom](https://loganthatcher.com/images/RoboRev/deathBoom.png)

  Animated particles fly out from units when they die.

![Image of Bullet Camera with Blur](https://loganthatcher.com/images/RoboRev/bulletCameraWithBlur.png)

  Motion blur is activated when the bullet camera is on.

![Gif of Camera Zoom](https://loganthatcher.com/images/RoboRev/camera_zoom.gif)

  Camera zoom when selecting a character

![Gif of Camera Zoom](https://loganthatcher.com/images/RoboRev/healthPowerupAndShooting1.gif)

  Collecting a health powerup and shooting -- 1

![Gif of Camera Zoom](https://loganthatcher.com/images/RoboRev/healthPowerupAndShooting2.gif)

  Collecting a health powerup and shooting -- 2

![Gif of Camera Zoom](https://loganthatcher.com/images/RoboRev/IdleAnimation.gif)

  Idle animation

![Gif of Camera Zoom](https://loganthatcher.com/images/RoboRev/PickingUpShotgun.gif)

  Picking up a Shotgun

![Gif of Camera Zoom](https://loganthatcher.com/images/RoboRev/ShotgunShotAndUnitDeath.gif)

  Shotgun shot and unit death

![Gif of Camera Zoom](https://loganthatcher.com/images/RoboRev/EnvironmentalMappingAndSkybox.gif)

  Environmental Mapping and Skybox

