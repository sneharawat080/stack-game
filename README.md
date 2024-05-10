# Stack Game - README

Welcome to the JavaScript Stack Game! This is an engaging and addictive game where you need to stack blocks as precisely as possible. This README will guide you through the setup, gameplay, and contributing to the project.

## Table of Contents

- [Project Overview](#project-overview)
- [Game Setup](#game-setup)
- [Game Instructions](#game-instructions)
- [Scoring and Gameplay](#scoring-and-gameplay)
- [Game Over and Replay](#game-over-and-replay)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The JavaScript Stack Game is a block-stacking game where you must stack moving blocks on top of each other as accurately as possible. The game becomes more challenging as you progress, with smaller blocks and increasing speed. It uses HTML, CSS, and JavaScript for its implementation, including the Three.js library for 3D graphics and GSAP for animations.

## Game Setup

To run the JavaScript Stack Game on your local environment, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/javascript-stack-game.git
   ```

2. Change into the project directory:
   ```bash
   cd javascript-stack-game
   ```

3. Open `index.html` in your web browser, or use a local web server to serve the project:
   ```bash
   # Using Python's built-in server
   python -m http.server
   
   # Using Node.js with http-server (if installed via npm)
   http-server
   ```

4. Open the provided URL in your web browser to start playing the game.

## Game Instructions

To play the JavaScript Stack Game, follow these instructions:

- **Objective**: Stack the moving blocks as accurately as possible. Blocks that don't align will be chopped off.
- **Controls**: Click anywhere on the screen or press the spacebar to place the moving block.
- **Game Start**: Click the "Start" button to begin. If the game is over, click or press the spacebar to restart.
- **Gameplay**: As you progress, the speed increases, and the blocks become smaller, making it more challenging to stack them.

## Scoring and Gameplay

- **Score**: Your score increases as you stack blocks successfully. The objective is to achieve the highest score possible.
- **Game Mechanics**: Blocks that don't align are chopped off, reducing the size of the next block. The game ends when the block is too small to stack.
- **Game Ready and Over**: The game starts in the "Game Ready" state. When you lose, the "Game Over" state is triggered, showing the final score.

## Game Over and Replay

When you lose, the game enters the "Game Over" state, showing your final score. Click anywhere on the screen or press the spacebar to restart the game.

## Contributing

Contributions are welcome! To contribute to the project:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bugfix.
3. Implement your changes and commit them with descriptive messages.
4. Push your branch to GitHub and open a Pull Request.

Ensure that your contributions align with the project's coding standards and don't introduce bugs or other issues.

## License

This project is licensed under the [MIT License](LICENSE). You can use, modify, and distribute the code as long as any derived works are licensed under the same terms.

---

Thank you for playing the JavaScript Stack Game! If you have any questions, feedback, or suggestions, feel free to create an issue on GitHub or contact the project maintainers.
