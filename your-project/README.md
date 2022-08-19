<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# PONG 
*[Daniela Versteeg]*

*[Data Analytics, Ironhack CDMX , 08/22]*

## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Creation](#creation)
- [Links](#links)

## Project Description
The game consists of not letting the ball touch the left or right side of the screen. Use the paddles to hit the ball back.

## Rules
The game is very simple - follow the following rules:

1. Move the left paddle using w for up and s for down.
2. Move the right paddle using the up and down arrows.
3. Make sure the ball doesn't bounce off any of the walls
4. If you miss the ball, point for the other team

## Creating Pong


Make sure you download the following libraries

import turtle
import os


Create a window:

Make sure to include the screen colour, title, height and width customization 



Before we start the game use a function to turn turtle animation on or off and set a delay for update drawings


Set your scores for two people at 0 


Create a paddle for each side. Remember to customize each one and use the correct coordinates to place them in the right spot on your window.
hint: these are also turtle objects


Create a code to remove the line created by the turtle for each object. Penup() can be used for this code 


If (0,0) coordinates are the middle of the screen, how can we make sure the paddle is on the right side? Use a code and coordinates to set a paddle on the right side and a paddle on the left side. .Goto() can be.  used for this example.



Create an object called Ball, customize the speed, shape, color. Remember that the ball will also have a line by default, remove it 
Ball


Set the ball to the center of the screen

Create a pen object to be set as the scoreboard - include what you would like to include in it. Customize it as you did
for all the other objects
Pen


Define 4 functions in order to move the paddles, use the ycor() turtle module:


Make a keyboard binding in order to call the function. When the user presses a button, call the function.
Keyboard bindings

Getting the game started 

Use a fuction to update the screen constantly, while loop will allow this constant update. In your loop include the ball movement, 
the conditions so that it doesnt bounce off the screen. 


The ball has to move on the screen - it needs to bounce off the walls and the paddles. Separate the ball into movement in terms of x coordinates and movements in terms of y coordinates. (this is part of the game loop)
 

In the border. checking part of your loop think about the height and width of your screen.

## Links
Include links to your repository, slides and kanban board. Feel free to include any other links associated with your project.

[Repository](https://github.com/)  
[Slides](https://slides.com/)  
[Trello](https://trello.com/en)  
