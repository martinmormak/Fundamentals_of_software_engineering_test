Tic-Tac-Toe (Piskvorky) – Console Game in C

This project is a simple console-based implementation of a Tic-Tac-Toe (Piskvorky) game written in C.

The game is played on a one-dimensional field of a user-defined size, where two players alternately place marks in an attempt to align three consecutive symbols.

Features
Dynamic field size defined by the user at runtime
Two-player turn-based gameplay (Player A and Player B)
Input validation for invalid or already occupied positions
Simple ASCII-based board rendering in the console
Win detection based on three consecutive marks (XXX)
Game Logic
Players take turns entering a position on the field
A move is accepted only if the position is valid and not already occupied
The game continuously checks for a winning condition (three consecutive Xs)
The game ends when a player achieves three in a row
Functions
draw() – renders the current game field
addCross() – handles player moves and validates input
isSolved() – checks if a winning condition is met
Purpose

The project demonstrates basic C programming concepts such as:

Arrays and memory manipulation
Input/output handling
Control flow and game loop logic
Simple game state management
