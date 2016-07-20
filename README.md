# RoboSaver
It is a 3D game made in Panda3D and uses Bullet Physics Engine

When you spawn on stair your objective is to collect coins in this level. You won't die in this level because this game is just the demo of environment and RobotMan. You, as RobotMan can jump and run, animation is done for Idle state, running and jumping state. Background music is provided by Timbre from FreeSound.com, Jumping and running sound is also implemented.
  
You can see health displayed on the top, coins collected is next to it. There are 5 coins in this level to collect. 
  
Timer is there in the center of DirectFrame, DirectFrame is used along with OnScreenText to show timer,coins and health.

Stairs have bulletPhysics, every alternate steps are rotating. You have to jump through each steps to go till last stairs and collect coins. In this level there are no AI's so it's pretty simple game. In next level you can expect to get punched and/or fired by the AI's and there will be health potions and boss fight. There will be secret dungeon where player need to answer certain questions correctly to increase his health and coins. It's like bonus points. 

You need to select particular set of stairs to go through. One stairs have coins and other has nothing. You can go through just one because time limit is less (I have kept time limit as 500seconds in this level so it easy for you to test all the workings of the game, time limit will be strict in level 2) . 

Camera  Controls- 
Camera can be controlled by 4 buttons on the keyboard.
"A" button, is used to move camera to left side of you, the player.
"D" button, is used to move camera to right side of the player. 
"W" button is used to move camera to the top side of the player.
"S" button is used to move camera to the bottom side of the player.

Player Controls  - 

"Up Arrow" button is used to make player go forward.
"Down Arrow" button is used to make player go backward.
"Left Arrow" button is used to make player turn left.
"Right Arrow" button is used to make player turn right.
"Ctrl" button is used to jump the player.
"Escp" button is used to exit the game.
"F3" button is used to get out of debug mode.
