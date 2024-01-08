#Snake_Game using python

Using module

pygame
1.pip install pygame(in command prompt)

2.open ide

Create the Screen:

Using module
To create the screen using Pygame, you will need to make use of the display.set_model Also, you will have to make use of the inito and the quito methods to initialize and uninitialize everything at the start and the end of the code.
The update) method is used to update any changes made to the screen. There is another method i.e flip( that works similarly to the update) function. The difference is that the update() method updates only the changes that are made .flip() method redoes the complete screen again.

Moving of snake:

To move the snake, you will need to use the key events present in the KEYDOWN class of Pygame. The events that are used over here are, K_UP, K_DOWN, K_LEFT, and K_RIGHT to make the snake move up, down, left and right, the display screen is changed from the default black to white using the fill method.
Icreated new variables x1_change and 1_change in order to hold the updating values of the x and y coordinates.

Game Over when Snake touch the boundaries:

Using module
if the player hits the boundaries of the screen, then he loses. To specify that, I have made use of an 'if' statement that defines the limits for the x and y coordinates of the snake to be less than or equal to that of the screen. Also, make a not over here that I have removed the hardcodes and used variables instead so that it becomes easy in case you want to make any changes to the game later on.


