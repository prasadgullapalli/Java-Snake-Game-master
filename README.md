# Java Snake Game

Snake is a classic video game that was first created in the late 1970s and later brought to PCs. In this game, the player controls a snake with the objective of eating as many apples as possible. Each time the snake eats an apple, its body grows. The snake must avoid the walls and its own body. This game is sometimes called Nibbles.

## Development of Java Snake Game

The size of each joint of the snake is 10 px. The snake is controlled with the cursor keys. Initially, the snake has three joints. If the game ends, a "Game Over" message is displayed in the middle of the board.

### Game Theory

1. **Board Dimensions**:
    - The game board is a 300x300 pixel area.
    - Each joint of the snake and each apple are 10x10 pixels.

2. **Snake Initialization**:
    - The snake starts with three joints.
    - The initial position of the snake is set at coordinates (50, 50) with each joint placed 10 pixels apart horizontally.

3. **Game Mechanics**:
    - The snake is controlled using the cursor keys.
    - The snake grows by one joint each time it eats an apple.
    - The game ends if the snake collides with the walls or its own body.

4. **Apple Placement**:
    - Apples are placed randomly on the board.
    - The position of the apple is recalculated each time it is eaten.

### Code Overview

#### Board.java

The `Board` class is responsible for the game board, game mechanics, and rendering.

