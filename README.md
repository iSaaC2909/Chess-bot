# Chess AI

This project implements a chess game with an AI opponent using Python and the Pygame library.

## Files

* `ChessEngine.py`:  Contains the `GameState` class, which stores information about the current state of the chess game, determines valid moves, and keeps a move log.
* `ChessAI.py`: Handles the AI's move generation using algorithms like minimax with alpha-beta pruning.  It evaluates board states and chooses the best move.
* `ChessMain.py`:  The main driver file. It handles user input, updates the game graphics, and displays the `GameState` object. It also manages the game loop and user interface.

## How to Run

1.  Ensure you have Python and Pygame installed.
2.  Place the image files for the chess pieces in a directory named `images` in the same directory as the Python scripts.
3.  Run `ChessMain.py` to start the game.

## Features

* **Graphical User Interface:** Uses Pygame to display the chessboard and pieces.
* **Two-Player Mode:** Allows two human players to play against each other.
* **AI Opponent:** Includes an AI that can play against a human player.  The AI uses the minimax algorithm with alpha-beta pruning to determine the best move.
* **Move Validation:** The engine validates all moves according to the rules of chess.
* **Game Logic:** Handles castling, pawn promotion, en passant captures, check, checkmate, and stalemate.
* **Move Logging:** Keeps track of all moves made during the game.
* **Undo Move:** Allows the player to undo the last move.
