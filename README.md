# Random-Ball-Movement
Graphics Animation Of The Random Walk 

In this project,we have three files i.e,

•	Index.html: This is the Html file where all elements are created. 
•	styles.css: This is the CSS file containing all the styles for the animation.
•	walk1.js: This is the JavaScript file containing all the functions need to active.

The walk1.js file contains code and comments ,here are some details:

•	The area variable is an object that defines the area of the screen in which the ball elements will be displayed. It has a set width and height, and a reference to the Html element called area. This reference is stored in the property element.
•	The initialize function creates the area div on the Html page.
•	The moveTo function takes a "ball" and "x,y" coordinates as parameters, then it sets the coordinates of that given ball to the given x,y coordinates.
•	The changeDirectionIfNecessary function takes a "ball" and "x,y" coordinates as parameters, then it determines whether the ball trajectory should be reversed if the ball hits the area bounds.
•	The create function has the following parameters as input:
•	color: This is a string representing the color of the ball (ex. red)
•	dx: The starting position of the ball on the x-axis
•	dy: The starting position of the ball on the y-axis
•	The update function has the following parameters as input:
•	ball: This is a reference to the ball
•	x: The new desired position of the ball on the x-axis
•	y: The new desired position of the ball on the y-axis

In create() function ,create a ball with the height and width required.
In update() function,move the ball randomly and update the positions of the ball
The update function should use the input ball, x and y to move the ball on the screen using the moveTo function. Then, it needs to check the direction the ball should move in using the changeDirectionIfNecessary function every sixteen milliseconds. It should also keep calling itself every sixteen milliseconds to keep the balls moving.

After these process were done ,the three balls were randomly moving inside the container.
