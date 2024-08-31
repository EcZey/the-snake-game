# Snake Game

Welcome to the Snake Game! This is a classic snake game implemented using Python's `turtle` graphics library. Navigate the snake to eat the food, grow, and achieve high scores!

## Project Overview

This project simulates the classic Snake game. The game features:
- A snake that grows longer each time it eats food.
- A scoring system that tracks your current and high scores.
- Collision detection with the walls and the snake's own body.

## Features

- **Snake Movement**: Control the snake using the arrow keys.
- **Food Generation**: The snake grows and scores increase when it eats food.
- **Scoreboard**: Tracks and displays the current score and the highest score.
- **Collision Detection**: Ends the game if the snake collides with the wall or itself.

## Requirements

- Python 3.10 or newer (Tested with Python 3.12)
- `turtle` module (comes with Python standard library)

## Usage

1. **Run the Game**:
   Execute `python main.py` to start the game.

2. **Controls**:
   - **Up Arrow**: Move the snake up.
   - **Down Arrow**: Move the snake down.
   - **Left Arrow**: Move the snake left.
   - **Right Arrow**: Move the snake right.

3. **Scoring**:
   - The score increases each time the snake eats the food.
   - The high score is saved and displayed.

4. **Exiting the Game**:
   - Click on the window to exit the game.

## Code Structure

- **`main.py`**: The main file that runs the game.
- **`snake.py`**: Contains the `Snake` class, which handles the snake's movement and growth.
- **`food.py`**: Contains the `Food` class, which manages the food's position.
- **`scoreboard.py`**: Contains the `Scoreboard` class, which handles the scoring and high score management.

## Object-Oriented Programming

This project uses Object-Oriented Programming (OOP) principles to structure the code:
- **Encapsulation**: Data and functionality related to the snake, food, and scoreboard are encapsulated within their respective classes.
- **Inheritance**: The `Scoreboard` and `Food` classes inherit from the `Turtle` class, allowing them to use turtle graphics functionality.
- **Modularity**: The project is organized into separate modules (`snake.py`, `food.py`, `scoreboard.py`) for better readability and maintainability.

