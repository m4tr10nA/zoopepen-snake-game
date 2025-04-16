# Snake Game

A simple snake game built with HTML and Phaser.js where the snake moves forward and can turn left or right to catch dots. Each time a dot is consumed, the snake grows longer and the score increases.

## How to Play

1. Open `index.html` in a web browser
2. Use the arrow keys to control the snake:
   - Left Arrow: Turn left
   - Right Arrow: Turn right
   - Up Arrow: Turn up
   - Down Arrow: Turn down
3. Eat the red dots to grow the snake and increase your score
4. Avoid hitting the walls or the snake's own body

## Features

- Snake moves continuously forward
- Turn left or right using arrow keys
- Snake grows when consuming dots
- Score tracking
- Automatic dot generation after consumption
- Game over on wall or self collision
- Increasing difficulty (snake speeds up as you eat more dots)

## Implementation Details

The game is built using:
- HTML5
- CSS for styling
- Phaser.js for game mechanics
- JavaScript for game logic

No installation is required as all dependencies are loaded via CDN.

## Game Controls

- **Arrow Keys**: Control the snake's direction
- The snake will continue moving in the current direction until you change it
- You cannot move directly opposite to the current direction (e.g., if moving right, you cannot immediately move left)

Enjoy the game! 