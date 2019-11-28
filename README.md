# SpaceInvaders

This repository is a project which contains a remake of the Space Invaders game programmed in C++ using Allegro libraries.

## 1 Description

Space Invaders is a 1978 arcade game created by Tomohiro Nishikado. It was manufactured and sold by Taito in Japan, and licensed
in the United States by the Midway division of Bally. Within the shooter genre, Space Invaders was the first fixed shooter and
set the template for the shoot 'em up genre. The goal is to defeat wave after wave of descending aliens with a horizontally 
moving laser to earn as many points as possible.

## 2 Design

The game has been designed using keyboard controllers as the user uses the cursor keys to operate the ship and to fire bullets
at enemy ships. In addition, while a game is in progress the player can also choose whether to play with background music or 
not. Using Allegro's libraries, the player can enjoy both a brilliant graphic interface and high quality soundtrack 
reproduction. Here it's going to be explained the different parts of which the game developed is composed.

### 2.1 Introduction 

Initially the game displays data about the game designer company, the date of creation and release, and copyright information as
shown in the following images.

IMAGES OF THE INTRODUCTION

### 2.2 Main and instructions menu

After completing the game presentation, the main game menu is displayed. In order to continue, the player must press the ENTER 
key. Next, the instruction screen is displayed, informing you which keys to use to move the ship and fire. This menu appears a
suitable time for the player to read it comfortably and then disappears.

IMAGE OF THE 

### 2.3 Options menu

After viewing the instructions, a new menu is displayed where the user can choose the difficulty of the game. Using the cursor 
arrows the user can choose in three game modes:

* Easy mode: the ship of the player has five lifes.
* Medium mode: the ship of the player has three lifes.
* Hard mode: the ship of the player has one lifes.

The difficulty is selected by pressing the ENTER key.

IMAGE OF THE OPTIONS MENU

### 2.4 Running the game!

This point is when the game begins, the player's ship starts at the center of the screen. Use the cursor keys to move the ship 
and use the space bar to shoot the villains. Be careful, the villains will be continually shooting at the player to try to kill
him. Fortunately there are a number of shields that can help in certain situations.

The following image shows a vision of the course of the game.

IMAGE OF THE GAME

### 2.5 How the game can end?

The game can finish in three ways:

* The player destroys all enemies and is feeble to have done so.
* Leaving the game by pressing the ESCAPE key.
* The player loses all lives 

If the game ends in one of the last two ways, you are informed that you have lost.

### 2.6 Game return

At the end of the game, a new menu is displayed in which you are given the opportunity to play again, choosing freely between 
each other and not. To do this, the player must press the ENTER key.

### 2.7 Playing audio tracks

As explained earlier, the game has a set of very high quality music tracks. While the game is in progress, the player can choose 
whether or not to listen to music. No soundtrack is played by default. If the user wants to play music he must press the key
with symbol + located on the right side of the keyboard. The player can choose from a total of eight tracks. After each beat, a
new track is played until the last one is reached. When you press again, playback is disabled and you return to the default
settings.

### 2.8 Game on pause

Since the player can at any time stop the execution of the game and then resume it, the feature of being able to pause the game
has been added. Pressing the TAB key pauses the game and stops the background music if one is active. To resume the game, the
player must press the tab key again.

### 2.9 Final

After asking the player if he wants to play again and answering no, the final credits of the game are shown. These credits show
the name of the game with the developer company and the year of creation, the soundtrack used referencing their original game
development companies in order to garantee the copyright.

## 3 Software used 

The following software has been used for the elaboration of the project:

* Codeblocks (version 17.12)
* Allegro libraries (version 4.7)
* Xpadder
* Photoshop CS6 
* Paint 3D

## 4 Tips

Some tips at the time of executing the program:

* To listen to music it is recommended **not to make consecutive pulsations** since the program is very sensitive to keyboard
  interruptions, causing problems when playing the music tracks.
* To run the program use the Script.bat file and don't start SpaceInvaders.exe.
* Pause the game before minimizing it by pressing the TAB key.

## 5 Test

In order to check the correct functioning of the program, different tests have been carried out. These tests have consisted in
the accomplishment of diverse games testing the different modes of departure, the response of the keys, the quality of the sound
effects and of the musical pitas. It has also been proven that the pause mode of the game and that the launch script runs on cmd
console without any problem.

## 6 Release

The release provided is a file with zip extension where the folder "images", the folder "soundtrack" have been compressed. the
folder "soundeffects", the executable file of the game and a script to run it in the cmd console. Do not delete the folders or
anything they save because otherwise the game will not work properly.