# Snake-game 🐍
This is a Python-based "Snake Game" built using the _'Turtle'_ graphics module. The game follows the classic Snake mechanics, where the player controls a snake that grows longer each time it eats food, and the objective is to avoid colliding with walls or the snake's own tail.

**Features**

- **Snake Movement**: The snake moves continuously, and the player can control its direction using the 'W', 'A', 'S', 'D' keys.
- **Food**: Each time the snake eats food, it grows longer, and a new piece of food appears in a random location.
- **Scoring**: The player's score increases each time the snake eats food, and the score resets upon collision with walls or the snake’s tail.
- **Collision Detection**: The game ends or resets if the snake collides with the screen boundaries or its own tail.

**Files**

- _'snake.py'_: Contains the _'Snake'_ class, responsible for the snake's movement and behavior.
- _'food.py'_: Contains the _'Food'_ class, which randomly places food on the screen.
- _'scoreboard.py'_: Contains the _'Scoreboard'_ class, responsible for keeping track of the score and displaying it on the screen.

**Game Mechanics**

1. **Snake Movement**: The snake is made up of segments, and its movement is controlled using the W, A, S, D keys.
    - W: Moves the snake upward.
    - A: Moves the snake left.
    - S: Moves the snake downward.
    - D: Moves the snake right.

2. **Food Collision**: When the snake's head collides with the food (within a distance of 15 units), the snake grows longer, and the score increases.

3. **Wall Collision**: If the snake's head hits the screen boundary (outside of 280 x 280 units), the game resets the snake and the score.

4. **Tail Collision**: If the snake's head collides with any part of its own body, the game resets the snake and the score.

5. **Score Reset**: The score is reset when the snake hits the wall or its tail.
