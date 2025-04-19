# Snake Game

## Overview

A classic implementation of the Snake game using Python and Pygame. Control a snake as it moves around the screen, eating food to grow longer while avoiding collisions with walls and itself.

## Demo

![Snake Game Gameplay](https://github.com/username/snake-game/raw/main/docs/snake_demo.gif)

## Features

- Smooth snake movement with keyboard controls
- Score tracking system
- Randomly generated food
- Game over detection for wall and self-collisions
- Simple and intuitive interface

## Requirements

- Python 3.6 or higher
- Pygame library

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Darshh16/Snake-game.git
cd snake-game
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required dependencies:
```bash
pip install pygame
```

## How to Play

1. Run the game:
```bash
python snake_game.py
```

2. Controls:
   - Use arrow keys (↑, ↓, ←, →) to change the snake's direction
   - Snake automatically moves in the current direction
   - Eat the red food blocks to grow longer and increase your score
   - Avoid hitting the walls or your own snake body

3. Game Over:
   - Press 'Q' to quit
   - Press 'C' to play again

## Customization

You can easily modify the game by changing variables in the code:

- `display_width` and `display_height`: Change the screen dimensions
- `block_size`: Adjust the size of the snake and food blocks
- `snake_speed`: Increase or decrease the difficulty

## Code Structure

- `game_loop()`: Main game function that controls the game flow
- `draw_snake()`: Renders the snake on the screen
- `display_score()`: Shows the current score
- `message()`: Displays text messages on the screen

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by the classic Snake game
- Built with [Pygame](https://www.pygame.org/)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
