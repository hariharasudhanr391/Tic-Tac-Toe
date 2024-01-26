# Tic-Tac-Toe
This is a simple implementation of the classic Tic Tac Toe game in Python. The game is played on a 3x3 grid, and two players take turns to place their marks (X or O) on the board. The game continues until one player wins by having three of their marks in a row (horizontally, vertically, or diagonally), or the game ends in a tie if the board is full.

## How to Play
- Run the code in a Python environment.
- The initial game board is displayed with numbered positions from 1 to 9.
- Players take turns entering the position where they want to place their mark.
- The game continues until there is a winner or a tie.
- The winner (X or O) or a tie is announced at the end of the game.

# Code Structure
## Global Variables:
- board: Holds the game board data.
- game_still_going: Indicates if the game is still in progress.
- winner: Holds the winner of the game.
- current_player: Indicates the current player (X or O).

## Functions:
- play_game(): Executes the main game loop.
- display_board(): Displays the current state of the game board.
- handle_turn(player): Handles a turn for the specified player.
- check_if_game_over(): Checks if the game is over (winner or tie).
- check_for_winner(): Checks if there is a winner.
- check_rows(), check_columns(), check_diagonals(): Check for a win in rows, columns, and diagonals.
- check_for_tie(): Checks if the game is a tie.
- flip_player(): Switches the current player.

# Execution:
The game is started by calling the play_game() function.

