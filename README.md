# Open Player Controller - A Free and Open Source Character Controller alternative for Unity Engine

## What is Open Player Controller?
Open Player Controller (OPC for short) is an open source Character Controller that makes a use of RigidBodies to move player around the scene.
<br>Built from the ground up with C#, OPC is a flexible character system which can be inmplemented into any type of project (FPS only currently).
<br>Its Modular system is one of the biggest perks. E.g, if you don't want your player to jump in your game/level, simply remove the script and OPC will do the rest.

<br><br><i>The project has started on 30 August 2016.</i>

## Why does this project exist?
<br>While the new RigidBody based Character Controller developed by Unity is a good, its codebase is too complex and there are sometimes features that developer doesn't need (e.g mobile input)
<br>Sure there are some good alternatives out there on the Asset Store, but they're costly and, to some extent, are complex too. <br><br>OPC is aimed to be used by beginner/professional indie developers who want to create a quick prototype for their games in Unity Engine.

## How can I help this project?
Open Player Controller is an open source project. 
Fork it as your own repository to make any modifications you want. Let's make OPC better together for everyone!
<br><br>
You're free to retain them and use for both commercial and non-commercial purposes (apart from directly selling scripts). 
<br><br>OPC is licensed under [MIT License](https://github.com/elmar1235/OpenPlayerController/blob/master/LICENSE.md).

# Features
Open Player Controller is currently is in active development (as of August 2016) with current  subject to alteration and implementation of future ones.
<br>For most up-to-date features, take a look at a [Trello Board](https://trello.com/b/GXjWg5oO).

## Current Features (2 September 2016)
* RigidBody based Player Locomotion
* Push other RigidBody objects with Player's mass
* Crouching - player can crouch underneath low objects by holding down Left Control button. Player's camera, and its collider, and movement speed, react to crouching
* Jumping (incomplete) - player can jump around
* * Climbing Ladders (experimental)

## Planned Features
* Player Prone
* Walking on Stairs without any need of an invisible ramp
* Swimming
* React to falling from high places (e.g fall damage)
* React to being crushed by a RigidBody Object taking its mass into consideration
* React to having a RigidBody Object thrown at taking its mass into consideration
* Many more planned (Third Person Shooter Player Controller?)

# How to get Started?

## Implementing Open Player Controller into Unity Project

This can be done by simply navigating to the "Prefabs" folder, where you can find a FPS Player Controller and dragging it into the scene.
<br><br>And that's pretty much it!

## Collaboration on a project
Please ensure that edited/added code is well commented before doing pull requests
