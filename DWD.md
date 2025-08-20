---
title: Dire Wolf Digital
layout: template
filename: DWD.md
---

# Dire Wolf Digital

Dire Wolf Digital is a Denver, Colorado based game studio. It focuses on both physical and digital strategy card and board games.

At Dire Wolf, Software Engineers were split into two teams, Server and Client. As a Client Engineer, I worked within Unity coding gameplay features, scripting UI and developing core tools. I also coordinated with designers, artists, and back-end engineers to integrate all their work and ideas into a finalized / cohesive version of the game.

I worked on many different titles, eventually rising to the Primary Client Engineer for Munchkin Digital and Clank! Digital. I was responsible for taking the initial prototype, alpha versions, of the games and developing them into finalized, production ready products. I was also the Lead Engineer for the three DLC expansions for Munchkin (Unnatural Axe, Clerical Errors, & Pixels and Papers) and one for Clank (Sunken Treasures).

## [Clank!](https://store.steampowered.com/app/1722870/Clank/)

Clank! is a deck-building game about adventuring down into a dungeon and getting out with your loot before the dragon is able to finish you off.

![Image of Clank!](https://loganthatcher.com/images/DWD/Clank_Opening.png)

I was the Primary Unity Engineer for Clank! for much of its development. During part of its development, I led a small team of other client engineers on the project. As part of my role on the project, I was responsible for coordinating with artists, designers and server engineers about the work and features, along with updating production and QA on the status of various features and the state of the game as a whole.

![Image of Dragon Attack in Clank!](https://loganthatcher.com/images/DWD/Clank_Attack.png)

During my time on Clank! I implemented many different systems. One of the larger elements that I worked on was updating the camera tech and systems used to control it. I updated the code to use the Unity Cinemachine system and created tools for dynamic object following, camera bounding, and compound camera movements so that all the controls that could be adjusted by the artists to allow them to create what they envision.

### [Clank! Sunken Treasures](https://store.steampowered.com/app/3550040/Clank__Sunken_Treasures/)

Sunken Treasures takes the original Clank formula and brings it under the waves. The players must face not only new monsters of the sea but also the dangers of the water itself less they drown in the depths. 

![Image of Sunken Treasures Expansion](https://loganthatcher.com/images/DWD/Sunk_Underwater.png)

Sunken Treasures was the first DLC Expansion for Clank!. In addition to adding the new gameplay features and visuals that the expansion brought, I also continued to make improvements to the base game as well. One of the larger additions was the path visualizations. 

![Image of movement paths in Clank!](https://loganthatcher.com/images/DWD/Sunk_Paths.png)

The base of the system was a Cubic Bezier Curve dynamically generated from the set of rooms the player had visited. It also needed to add variations to reduce overlaps between players and for players doubling back on their own paths. Controls were created to allow the artists to adjust the curvature, offsets, render speed, color gradients and more.

## [Munchkin Digital](https://store.steampowered.com/app/1722860/Munchkin_Digital/)

Munchkin is based on the vibe of playing Dungeons and Dragons in a basement with your friends, full of the 90's humor to match. Players gear up their character, kick down the doors of the dungeon, and try to rush their way to be first to max level. 

![Image of Munchkin](https://loganthatcher.com/images/DWD/Munchkin_Kick.png)

I began work on Munchkin at the first playable prototype stage, then rose to Primary Unity Engineer for moving from Beta/Early Access to the Full Release. Munchkins posed several interesting challenges to digitizing. First, many of the cards are of the form "break this base rule" which required far more robust and flexible systems to handle it, without needing to write everything when adding cards from expansions or having to have special case handling for each one. Second was the social nature of the game, which is not just in the deal making and back stabbing between players, but in the very nature of the more loose and interpretive nature in which rules and cards are written. There is an informal rule to Munchkin that "the last player still arguing is correct". 

### Munchkin Expansions
For the Expansions to Munchkin I was lead engineer. The first expansion set, [Unnatural Axe](https://store.steampowered.com/app/2392090/Munchkin_Digital__Unnatural_Axe/), was a proving ground for how well the existing system could handle adding new cards and mechanics. It included refining and expanding systems to improve the overall game and laying the groundwork for making future expansions easier.

![Image of Munchkin Inventory](https://loganthatcher.com/images/DWD/Munchkin_Inventory.png)

[Clerical Errors](https://store.steampowered.com/app/2840360/Munchkin_Digital__Clerical_Errors/) benefited from the systems work that had been established but still brought with it its own challenges, as it had some higher complexity cards and more lingering effects. With the additions and the growing card pool, how to present information to the player was a growing challenge.

![Image of Munchkin Combat](https://loganthatcher.com/images/DWD/Munchkin_Combat.png)

[Pixels and Paper](https://store.steampowered.com/app/3008510/Munchkin_Digital__Pixels__Paper_Promos/) was a small cross promotional set, with a physical release that came with the cards and digital keys for both the base game and this expansion. It was able to be more rapidly developed even with the unique and novel designs, due to the work I had done in previous expansions.

## [Everdell](https://store.steampowered.com/app/1722840/Everdell/)

Everdell is a tableau building and worker placement game where players send forest critters to gather resources and build a city
On Everdell I worked on the drag and drop system combining 2D UI space with the 3D critter model and environmental board.

![Image of Everdell](https://loganthatcher.com/images/DWD/Everdell.png)

## [Wings of Glory](https://store.steampowered.com/app/965620/Wings_of_Glory/)

Wings of Glory was the first project I worked on at Dire Wolf. It is a game about taking your squad of WW1 era biplanes on missions and dog fighting vs your opponent’s squad.

![Image of Wings of Glory](https://loganthatcher.com/images/DWD/WingsOfGlory.png)
