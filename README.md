# Tic-Tac-Toe Game in Python

This repository contains a simple command-line implementation of the classic Tic-Tac-Toe game. The game is designed for two players and follows the traditional rules of Tic-Tac-Toe.

## Features

- **Two-player game:** Play against another person in a turn-based format.
- **Game board display:** The game board is displayed after each move.
- **Automatic win detection:** The game automatically detects when a player has won or if the game ends in a tie.
- **Easy to understand code:** The code is structured with clear functions, making it easy to follow and modify.

## How to Play

1. **Run the game:** The game can be run directly from the command line by executing the `main.py` file.
2. **Make a move:** Players take turns to place their mark (X or O) on the board by entering a position number (1-9).
3. **Winning the game:** The first player to align three of their marks horizontally, vertically, or diagonally wins the game.
4. **Game ends:** The game will automatically end when a player wins or if the board is full with no winner (a tie).

## Code Structure

- **Global Variables:**
  - `board`: A list representing the game board.
  - `game_still_going`: A boolean flag indicating if the game is ongoing.
  - `winner`: A variable to store the winner's identity.
  - `current_player`: A variable to track whose turn it is.

- **Functions:**
  - `play_game()`: The main function that starts and manages the game loop.
  - `display_board()`: Displays the current state of the game board.
  - `handle_turn(player)`: Manages the current player's turn, including input validation.
  - `check_if_game_over()`: Checks if the game has ended by win or tie.
  - `check_for_winner()`: Determines if there is a winner.
  - `check_for_tie()`: Checks if the game board is full and the game is a tie.
  - `flip_player()`: Switches the turn between the two players.

## How to Run

To play the game, simply clone the repository and run the `main.py` script using Python 3.x:

```bash
git clone https://github.com/your-username/tic-tac-toe.git
cd tic-tac-toe
python3 main.py
```

## Example Gameplay

```
X | - | -
---------
- | O | -
---------
X | - | O

Player X, choose your move (1-9): 7

X | - | X
---------
- | O | -
---------
X | - | O

Player O, choose your move (1-9): 5
```

## Contributing

Feel free to fork this repository and submit pull requests if you would like to add features or fix bugs. Contributions are welcome!

---

This README provides a comprehensive overview of the Tic-Tac-Toe game, including how to play, how the code is structured, and how to run the game.
