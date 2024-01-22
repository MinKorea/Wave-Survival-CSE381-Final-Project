# You can download and play the game by this link:

https://drive.google.com/file/d/1gNfdKXqFsBRQKqyfN7MDjELey4zaQX9B/view?usp=sharing

# Game Design Description - Min Kwak, Alexander Gentile


## INTRODUCTION
This document describes a game called "Wave Survival", which is designed to be a simple TPS game. The game will employ 3d animation, background maps, collision detection, physics, AI, side scrolling & gravity, efficient memory management, render threading, and more 3D game techniques.


## TECHNOLOGY
Wave Survival will be developed by using the Unreal Engine 5. Blueprints and C++ will be used for implementing main game-playing algorithms. Models of characters and environment will be from the Unreal marketplace. 


## BACK STORY
A mystery person kidnapped the main character. When he woke up, he saw a rifle and the message that he needed to survive and find the key to the portal to escape here and go back to his home. (The back story can be modified by implementing the game environments and getting the assets from the Unreal marketplace)


## OBJECTIVE
The main character is isolated in the battle map. He wants to get out of there. There is a portal for getting out of the map, but he needs to find the key for opening the portal first. So what he should do is survive the enemies attacking there, find the key, and escape there.


## GAMEPLAY
The game will work like a Third-person shooter, with the main character able to run, and jump up or shoot the enemies. Enemies move around the map randomly, but when the enemies recognize the player, they chase and attack you. There are waves in which new enemies are spawned, and there will be 10 waves(or more). The enemies will be stronger for every wave. When the player clears all of the waves(it’ll be super hard), the hidden boss comes out, and if the player kills him, then the boss drops the key, so the player can escape the map. If the player dies before 10 waves, the score will be displayed. 


## CONTROLS
This game will be played using both a keyboard and a mouse. Once started, use the following:

W - Move Front

S - Move Back

A - Move Left 

D - Move Right 

SPACE - Jump

Click - Shooting

ESC - This pauses the game and presents a pop-up window to the player asking them to continue when they are ready. If a game is not in progress, ESC does nothing.

0 - Skip waves for testing.


## GRAPHICAL USER INTERFACE
As far as the GUI is concerned, if we consider

Splash Screen - The splash screen GUI presents a game logo and a Start button for users to press when they are ready to play. If pressed, the main menu will appear.

Main Menu - When the splash screen is pressed, the main menu will appear which allows the player to select from the following options:

New Game - The first wave of the game will start when this button is pressed.

Display Controls - If pressed, the game will display an info screen with a description of all game controls.

About - If pressed, the game will display an info screen with information about the game author.

Exit - If pressed, the game program will exit.

In-Game Menu - While the game is in progress, we'll always have a game menu that allows the player to select from the following options:

New Game - If a game is in progress, first we'll pop up a dialog to make sure the user wants to quit the current game. If we conclude the user wants to start a game, then the game state is reset and begun.

Pause Game - This button is deactivated when a game is not in progress. If pressed, it will produce the same effect as the ESC key.

Display Controls - If pressed, the game will display an info screen with a description of all game controls.

Leaderboard - If pressed, the game will display a leaderboard of scores

About - If pressed, the game will display an info screen with information about the game author.

Exit - If pressed, the game program will exit.

In-Game GUI - Once a game starts, a 3-2-1-Begin sequence is counted down and displayed for the player to see. The counts of the wave will be displayed on the screen. While playing the following will be displayed at all times:
- Score
- Enemies Remaining
- Player ability level.


## ARTWORK
All artwork in the game will be original or from the unreal marketplace. 

The following needs to be created:

Main Character: It’ll be a person-shaped model. The model and animations will be from the unreal marketplace.

Animations needed: Running, Jumping, Shooting.

Map: the whole map will be designed by using some assets of the marketplace, and the assets will be placed on the map properly so that the player can fight enemies in various environments.

Enemies: It can be a monster or person-shaped. The model and animations will be from the unreal marketplace.

Animations needed: Moving, Attacking.

Other artworks will be from the marketplace or designed originally if needed. 


## SOUND EFFECTS 
All sound effects will be from Unreal Marketplace. Sounds will be made to coincide with each of the following events when time permits:

- Walking
  
- Jumping

- Shooting

- Collision effects (Taking Damage)

- Getting & Using an Item

- Dead

- Clear the wave


##MUSIC
Game Music will be added when time permits.

