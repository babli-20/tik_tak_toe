# Tic Tac Toe - Python Console Game

## Overview
This is a simple console-based Tic Tac Toe game implemented in Python. It allows two players to take turns and play against each other in a classic 3x3 Tic Tac Toe board. The game runs in the command line and announces the winner once a player has successfully placed three of their marks in a row, column, or diagonal.

## How to Play
1. The game starts with an empty 3x3 board.
2. Player X goes first, followed by Player O.
3. Each player selects a position on the board (0-8) to place their mark.
4. The game continues until a player wins or the board is full.
5. The game announces the winner or a draw if no more moves are available.

## Game Rules
- The game follows standard Tic Tac Toe rules.
- The first player to align three marks (X or O) in a row, column, or diagonal wins.
- If the board is full and no player has won, the game ends in a draw.

## Running the Game
To play the game, run the following command in a Python environment:
```sh
python tic_tac_toe.py
```

## Code Explanation
### `sum(a, b, c)`
A helper function to sum three values to check winning conditions.

### `printBoard(xState, zState)`
Displays the current state of the Tic Tac Toe board.

### `checkWin(xState, zState)`
Checks if either player has won by evaluating all possible winning combinations.

### `Main Loop`
- Initializes the game board.
- Alternates turns between X and O.
- Takes user input to mark positions.
- Checks for a winner after each move.

## Example Game Play
```
Welcome to Tic Tac Toe
0 | 1 | 2
--|---|---
3 | 4 | 5
--|---|---
6 | 7 | 8
X's Chance
Please enter a value: 4
...
X Won the match
Match over
```

## Future Enhancements
- Add an AI opponent to play against the computer.
- Implement a GUI version using Tkinter or Pygame.
- Include error handling for invalid inputs.

## License
This project is open-source and free to use.

