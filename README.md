# 🐍 Snake Game

This repository contains a classic Snake Game implemented in Python using the `turtle` module. The game is simple yet entertaining, challenging players to navigate a growing snake while avoiding collisions.

## Features

- **Classic Gameplay**: Navigate the snake to eat food while avoiding walls and itself.
- **Scoreboard**: Tracks the player's current and high scores.
- **Dynamic Difficulty**: The snake grows longer with every food consumed, increasing the challenge.
- **Customizable Design**: Modify game elements such as colors, shapes, and screen size.

## Files Overview

### Source Code

- **`main.py`**: The entry point of the game, manages game flow, screen setup, and interactions.
- **`snake.py`**: Contains the `Snake` class, which handles the snake's movement, growth, and direction control.
- **`food.py`**: Defines the `Food` class to generate random food positions on the screen.
- **`scoreboard.py`**: Implements the `Scoreboard` class to display and update scores.
- **`score.py`**: A modified version of the scoreboard with persistent high-score functionality.

### Compiled Files

- **`.pyc files`**: Precompiled Python files for faster execution.

### Supporting Files

- **`data.txt`**: Stores the high score persistently.

## How to Play

1. **Run the game**: Execute `main.py` in your Python environment.
2. **Control the snake**: 
   - Use the arrow keys to navigate the snake (`Up`, `Down`, `Left`, `Right`).
3. **Objective**: 
   - Collect as much food as possible to increase your score.
   - Avoid running into the walls or the snake's own body.
4. **Game Over**: If a collision occurs, the game ends, displaying the final score and the high score.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/snake-game.git
   cd snake-game
