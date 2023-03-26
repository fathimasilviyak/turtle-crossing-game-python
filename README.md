# turtle-crossing-game-python

There is a whole bunch of randomly generated cars which are going horizontally across the screen.

The turtle is the player who has to cross the screen.

The player can control the turtle which can go forwards and backwards.

Once the player reaches the other side of the screen, the cars speed up, but the player goes back to the starting position, ready to cross the screen again.

When the player turtle hits a car, then that is the game over.  
 
### Working of the game

* A turtle moves forwards when the "Up" key is pressed and moves backwards when the "Down" key is pressed.

* Cars are randomly generated along the y-axis and will move from the right edge of the screen to the left edge.

* When the turtle hits the top edge of the screen, it moves back to the original position and the player levels up. On the next level, the car speed increases.

* When the turtle collides with a car, it's game over and everything stops.

Here this game is implemented using turtle, a python library.

Link for turtle documentation: https://docs.python.org/3/library/turtle.html

