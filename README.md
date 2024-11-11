# 01. Connect Four Game
## <a href="https://github.com/boriskostadinov96/Games/blob/main/connect_four_game.py">Link to gane</a>

## Overview:
This Connect Four Game is a terminal-based application that lets two players compete in a classic Connect Four game on a 6x7 grid. The objective of the game is for a player to get four consecutive pieces in a row, column, or diagonal. The game enforces turn-taking, checks for valid moves, and detects winning conditions. It’s built entirely in Python, focusing on essential game logic and user input validation.

# Features:
- Two-Player Gameplay:
Players take turns selecting a column to drop their piece, alternating between Player 1 and Player 2.

- Winning Condition Detection:
Checks if the current move creates four consecutive pieces horizontally, vertically, or diagonally

- Error Handling:
  Detects and handles cases where a player attempts to place a piece in a full column.
  Validates column selections to ensure they’re within the allowed range.

- Game End Conditions:
  Declares the winner if a player successfully connects four pieces.
  Declares a draw if the board is completely filled without any player winning.


# How It Works:
- Game Board Setup:
A 6x7 board is created, initialized with zeros to represent empty cells.

- Player Turn:
Each player is prompted to choose a column to place their piece.
If the column is valid and not full, the piece is added to the lowest available row in that column.
The game displays the board after each move.

- Win and Draw Conditions:
After each move, the game checks for four consecutive pieces for a potential win.
If no winning move is detected and the board is full, the game ends in a draw.

- The image is then displayed within the application's window.

# End of Game:
The game announces the winner or a draw and exits.

To use this project, you need an API key from EdenAI to access their image generation services. You can set your API key in the get_image_url() function's header section.
