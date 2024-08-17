# TicTacTactician

This is a simple Tic-Tac-Toe game implemented using Python and Pygame, featuring a computer opponent that uses the Minimax algorithm to play optimally.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Minimax Algorithm](#minimax-algorithm)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)


## Features

- **Single-player Mode:** Play against the computer.
- **AI Opponent:** The computer uses the Minimax algorithm to make optimal moves.
- **Graphical Interface:** Built using Pygame for a simple and interactive gaming experience.
- **Responsive Game Board:** The game board dynamically updates as players make moves.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Navnoorsinghmahal/TicTacTactician.git
   ```
3. **Navigate to the Project Directory:
```bash
cd TicTacTactician
```

4. Install the Required Dependencies:
   Ensure you have Python installed. Then, install the dependencies:

``` bash
pip install pygame numpy
```

5. Run the Game:
   
```bash
python tictactactician.py
```

## How to Play

- **Objective:** The goal is to get three of your marks in a row (horizontal, vertical, or diagonal) before the computer does.
- **Player vs. AI:** You play as the first player (X), and the computer plays as the second player (O).
- **Gameplay:** Click on any empty square to place your mark. The computer will automatically take its turn after yours.

## Minimax Algorithm

The Minimax algorithm is used in this project to enable the AI to make the best possible move. It explores all possible game states and chooses the move that minimizes the possible loss for the worst-case scenario.

- **Maximizing:** The AI seeks to maximize its score by choosing moves that give it the highest possible outcome.
- **Minimizing:** When it’s the player’s turn, the AI assumes the player will make moves that minimize the AI's score.

## Project Structure
```bash
TicTacTactician/
├── tictactactician.py # Main game script
├── README.md # Project README file
└── requirements.txt # Project dependencies

```


## Technologies Used

- **Python**: Core language used for development.
- **Pygame**: Library used to create the graphical interface and manage game events.
- **NumPy**: Library used for handling the game board as a 2D array.


