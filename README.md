Tic Tac Toe (Console)

A classic 2-player Tic Tac Toe game built in Java, played entirely in the console. Players take turns entering row and column coordinates to place their mark, with win detection across rows, columns, and diagonals.

Features


2-player gameplay (Player X vs Player O)
3x3 board printed to the console after every move
Input validation — rejects moves on already-occupied cells
Win detection for rows, columns, and both diagonals
Turn switching handled automatically after each valid move


Tech Stack


Java (no external libraries)


How to Run


Clone the repository


bash   git clone <your-repo-url>
   cd <repo-folder>


Compile the source file


bash   javac tictactoe/TicTacToe.java


Run the game


bash   java tictactoe.TicTacToe

How to Play


The board uses 0-indexed rows and columns (0, 1, or 2)
On your turn, enter the row and column separated by a space (or Enter) when prompted
Example: to place your mark in the top-left cell, enter 0 then 0
Player X always goes first, then turns alternate
The game ends when a player gets 3 in a row (horizontally, vertically, or diagonally)


Example session

-------------
|   |   |   |
-------------
|   |   |   |
-------------
|   |   |   |
-------------
PlayerX enter: 
0
0
-------------
| X |   |   |
-------------
|   |   |   |
-------------
|   |   |   |
-------------
PlayerO enter: 
1
1
...

Project Structure

tictactoe/
└── TicTacToe.java   # Game logic, board printing, win detection, and main loop

Future Improvements


Add a "draw" check for when the board fills up with no winner
Validate row/column input bounds (currently assumes valid 0-2 input)
Add a play-again option instead of exiting after one game
Build a GUI version using Java Swing
