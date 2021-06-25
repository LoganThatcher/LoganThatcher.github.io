---
title: Legend of Kyle
layout: template
filename: LegendOfKyle.md
---

# Project Summary

Legend of Kyle is a top down dungeon crawler style game. There are multiple different types of enemies, 
giving the game elements of a shoot 'em up. The character gains various abilities to provide 
options to choose their own playstyle.

### Development

This game was built in Unity with a five person team. My primary contribution to the game was 
a system for the creation of enemies (monsters). They were designed using a code structure 
that made it easy to interchange individual pieces to minimize repetition of code, while still providing 
a high degree of flexibility in behavior. I also contributed to visual aspects through my work on 
the camera movements, character animation, and particles. Within the team, I provided leadership, 
focused the direction of the project, and coordinated the integration of the game components.

The game is playable on Kongregate at this [link](https://www.kongregate.com/games/SpikeHammer/the-legend-of-kyle)



## Game Overview

![GIF of Fight 3](https://loganthatcher.com/images/LoK/GIFs/Fight3.gif)

The main loop of the game is entering a room in the dungeon and killing all the monsters to move to the next room.
Ultimately trying to find the Boss Room and defeat it to move to the next level.

## Start of Game

![Image of Opening Story](https://loganthatcher.com/images/LoK/images/OpeningStory.png)

The game begins by establishing the quest and giving a short backstory.

<br>

![Image of Over World Start](https://loganthatcher.com/images/LoK/images/OverWorldStart.png)

There is an overworld where players can choose which level to play and 
are given additional information and storyline at various points.


## Tutorial Section

![GIF of Tutorial](https://loganthatcher.com/images/LoK/GIFs/TutorialButtons.gif)

The tutorial presents a series of basic rooms as well as UI overlays to teach the basic game controls
(movement, melee attack, ranged attack, and rolling)

<br>

![GIF of Arrow Charging](https://loganthatcher.com/images/LoK/GIFs/ArrowCharging.gif)

The ranged attack has a charge up time that affects the speed, distance, and damage of the arrow that is fired.
 The UI icon of a bow in the top right hand corner appears and shows the string pulling back as it charges.

<br>

![GIF of Fight 1](https://loganthatcher.com/images/LoK/GIFs/Fight1.gif)

This is a basic fight in a dungeon room.

<br>

![GIF of Splitter Monster](https://loganthatcher.com/images/LoK/GIFs/SplitterMonster.gif)

Throughout the game, the monsters increase in complexity and ability.  This first monster splits in half the 
first time it is killed.

<br>

![Image of Boss Door](https://loganthatcher.com/images/LoK/images/BossDoor.png)

Boss doors purple and have particles rising out of them.

<br>

![GIF of Boss Fight 0](https://loganthatcher.com/images/LoK/GIFs/BossFight0.gif)

The tutorial boss is a version of the Splitter Monster that is larger and splits an additional time.

<br>

![Image of End of Level Screen Tutorial](https://loganthatcher.com/images/LoK/images/EndofLevelScreenTutorialSmall.png)

Once the boss has been defeated, the player is presented with game statistics showing how well they did.


## Power ups

![GIF of Power Ups](https://loganthatcher.com/images/LoK/GIFs/PowerUps.gif)

Monsters have a small chance of dropping a power up on death. There are three possibilities:
a heal (the heart), a temporary speed boost (the lightening bolt), or temporary invulnerability (the star).
The player emits corresponding particles while the buffs are active.


## Level 1

![GIF of Path 0](https://loganthatcher.com/images/LoK/GIFs/Path0.gif)

Having completed the tutorial, the player returns to the overworld and the character makes their way to Level 1 

### New Monsters 

![GIF of Cross Shooter](https://loganthatcher.com/images/LoK/GIFs/CrossShooter.gif)

This monster shoots 4 projectiles at a time

<br>

![GIF of Rusher](https://loganthatcher.com/images/LoK/GIFs/Rusher.gif)

This monster rushes toward the player quickly, pauses, and then rushes forward again.


### Sample Level 1 Gameplay

![GIF of Fight 3](https://loganthatcher.com/images/LoK/GIFs/Fight3.gif)

As levels progress, fights become more hectic and challenging.

<br>

![Image of Mini Map](https://loganthatcher.com/images/LoK/images/MiniMap.png)

The player has a minimap to help them navigate the dungeon. Information is added as they move to new rooms,
making the map grow. The room that the player is currently in is brighter than the other rooms.

<br>

![GIF of Boss Fight 1](https://loganthatcher.com/images/LoK/GIFs/BossFight1.gif)

The Boss has more health than a normal enemy and has a fixed pattern of strong attacks. 


## Level 2

![GIF of Path 1](https://loganthatcher.com/images/LoK/GIFs/Path1.gif)

Having completed Level 1, the character makes a beeline directly to Level 2.

<br>

![GIF of Teleport Tutorial](https://loganthatcher.com/images/LoK/GIFs/Teleport.gif)

On this level, the player is given a new ability to teleport a short distance. There is a ability icon
that appears under the health bar when it is ready to use. Teleporting can help a player escape from sticky situations.

### New Monsters

![GIF of ZigZag](https://loganthatcher.com/images/LoK/GIFs/ZigZag.gif)

This monster shoots projectiles that zig-zag.

<br>

![GIF of TriShooter](https://loganthatcher.com/images/LoK/GIFs/TriShooter.gif)

This monster shoots 3 projectiles simultaneously in an arc.

<br>

![GIF of Spiral](https://loganthatcher.com/images/LoK/GIFs/Spiral.gif)

This monster generates a spiral of projectiles around them.


### Sample Level 2 Gameplay

![GIF of Fight 4](https://loganthatcher.com/images/LoK/GIFs/Fight4.gif)

Monsters now have one more health and there tends to be more monsters in a room. This  
leads to more projectiles filling the room.

<br>

![GIF of Boss Fight 2](https://loganthatcher.com/images/LoK/GIFs/BossFight2.gif)

The boss for this level has more complex attacks and has a different attack animation for each one to 
signal what he is going to do.


## Level 3

![GIF of Path 2](https://loganthatcher.com/images/LoK/GIFs/Path2.gif)

Having completed Level 2, the character heads excitedly to the final level.

<br>

![GIF of Wind Blast](https://loganthatcher.com/images/LoK/GIFs/WindBlast.gif)

The player is given another new ability that allows them to push away both monsters and objects in the dungeon.
This provides the player a tool to deal with large numbers of enemies by making space and dealing damage.
There is another icon under the health bar that indicates when the ability is ready.

### New Monsters

![GIF of Bouncer](https://loganthatcher.com/images/LoK/GIFs/Bouncer.gif)

This monster fires projectiles that bounce off of walls and objects in the room.

<br>

![GIF of Lava Spitter](https://loganthatcher.com/images/LoK/GIFs/LavaSpitter.gif)

This monster fires projectiles that create pools of lava that damage the player when they stand in it.

<br>

![GIF of Shield](https://loganthatcher.com/images/LoK/GIFs/Shield.gif)

This monster holds a shield in front of it that blocks all types of attack, requiring the player to 
take advantage of the monster's slow turn rate.

<br>

![GIF of Spinner](https://loganthatcher.com/images/LoK/GIFs/Spinner.gif)

This monster has four orbs that spin around it and damage the player.


### Sample Level 3 Gameplay

![GIF of Fight 6](https://loganthatcher.com/images/LoK/GIFs/Fight6.gif)

Fights in Level 3 tend to be even more complicated and challenging, requiring the player to use 
a wider range of tactics to be successful.

<br>

![GIF of Boss Fight 3](https://loganthatcher.com/images/LoK/GIFs/BossFight3.gif)

This boss generates lots of projectiles and lava pools creating a more dangerous environment which
 requires the player to be more aware of their movement and the threats in the room.

## End of Game

![GIF of Path 3](https://loganthatcher.com/images/LoK/GIFs/Path3.gif)

Clearing all 3 dungeons, the character takes a bit of a victory lap.

<br>

![Image of Ending Story](https://loganthatcher.com/images/LoK/images/EndingStory.png)

The player is presented with the end of the storyline, with them having successfully saved the kingdom.