
# 🐍 Snake Game

This project is a Python implementation of the classic **Snake Game** using the `turtle` graphics library. In this game, you control a snake that grows longer each time it eats food. The objective is to eat as much food as possible without running into the walls or colliding with your own tail. As the snake grows, the game becomes more challenging.

## Game Features
- **Snake Control**: Move the snake using the `W`, `S`, `A`, and `D` keys.
- **Food Collection**: The snake grows longer with each piece of food it eats, and new food appears at random locations on the screen.
- **Scoreboard**: Displays the current score, and shows a "Game Over" message when the game ends.

## How to Run

### Prerequisites
- Python 3.x installed on your system.
- `turtle` is a standard Python module, so no external dependencies are required.

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/snake-game.git
   ```

2. Navigate to the project directory:

   ```bash
   cd snake-game
   ```

3. Run the game:

   ```bash
   python main.py
   ```

### Game Controls
- Press `W` to move the snake **up**.
- Press `S` to move the snake **down**.
- Press `A` to move the snake **left**.
- Press `D` to move the snake **right**.

## Files

`main.py`: This is the entry point of the game. It initializes the game, listens for key presses to control the snake, and handles the game loop, including collision detection with food, walls, and the snake's tail.
`snake.py`: Contains the `Snake` class, which handles the movement, creation, and behavior of the snake, including methods to change direction and extend the snake's length.
`food.py`: Contains the `Food` class, which randomly places food on the screen. The food is represented by a small circle that the snake can "eat" to grow longer.
`scoreboard.py`: Contains the `Scoreboard` class, which manages the score display and the "Game Over" message. It updates the score each time the snake eats food and ends the game when the snake collides with the wall or its tail.

##<p align="center">Example</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4ac7a623-4c0c-470c-8f00-7b29a22c61d9" alt="snake_game gif" width="300" height="300">
</p>

