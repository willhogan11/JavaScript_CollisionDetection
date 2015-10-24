###### Graphics Programming - Exercise 5
# Collisions
In this exercise we will look at various types of collisions on the canvas.

## Exercises
Save each exercise as a separate source file.

1. Create a blank HTML file with a CSS section and a JavaScript section. Add a canvas to it.

1. Create an init() function that re-sizes the canvas to 400x400, and call it.

1. Create a ball object that has a position, a velocity and an acceleration.

1. Add a draw function to the ball that draws the ball on the canvas.

1. Add a move function to the ball that moves the ball forward.

1. Use requestAnimationFrame to move the ball, clear the canvas, and draw the ball.

1. Add functionality to the ball's move function to detect a collision with the walls and have the ball bounce off them.

1. Create a constructor for a blue rectangle object, that can be drawn on the screen at a specified location.

1. Create ten of these rectangles, and place them in random locations on the canvas.

1. Have the rectangles disappear upon impact with the ball.

## Advanced exercises

1. Add a parameter to your function that is called by requestAnimationFrame and log it to the console. Examine the console output and investigate what the value is.  Change your ball's move function to use the timestamp to move the ball, rather than moving it a fixed amount every frame.

1. Create a grid of red rectangle at the top of the canvas taht disappear upon impact with the ball.

1. Have the ball bounce off the rectangles upon impact.

## Notes

- A very good collisions tutorial exists in [this blog post](http://www.html5rocks.com/en/tutorials/canvas/notearsgame/).
