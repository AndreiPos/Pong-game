# Pong-game

This Pong game is a simple implementation written in Python using the Turtle graphics library. It provides a classic arcade-style experience where players control paddles to hit a ball back and forth. The game is played on a green-colored window with dimensions of 800x600 pixels.

**Instructions**

1. Run the game by executing the Python script.
2. Use the following controls to move the paddles:
   * Player A (left paddle):
 
          I. Move Up: Press the "w" key 
          
          II. Move Down: Press the "s" key
   * Player B (right paddle):
   
          I. Move Up: Press the Up arrow key 
          
          II. Move Down: Press the Down arrow key
3. The objective of the game is to prevent the ball from hitting your side of the screen and score points by making the ball pass your opponent's paddle.
4. The game continues until one player reaches the winning score (not implemented in this version).


**Scoring**

* Each time the ball passes Player A's paddle and hits the right wall, Player B scores a point.
* Each time the ball passes Player B's paddle and hits the left wall, Player A scores a point.
* The current score of both players is displayed at the top center of the game window.


**Game Mechanics**

* The ball moves at a constant speed in both the horizontal (dx) and vertical (dy) directions.
* The paddles can only move vertically and are confined within the game window.
* When the ball collides with the top or bottom wall, it changes its vertical direction (dy) to bounce back.
* If the ball hits one of the paddles, it changes its horizontal direction (dx) to simulate a bounce.

**Contributions**

Contributions to the project are welcome. If you would like to enhance the game or fix any issues, please follow these steps:

1. Fork the repository.
2. Make your desired changes.
3. Test the game to ensure that it functions correctly.
4. Create a pull request, explaining your changes and the problem they solve.

Please feel free to report any issues or suggest improvements in the project's issue tracker.

Enjoy playing Pong!
