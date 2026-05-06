🎮 Game – Turn-Based X Placement Game
📌 Project Description

This is a simple console-based two-player game (Player A and Player B). Players take turns placing the symbol 'X' into a one-dimensional array (field). The winner is the player who first creates three consecutive X symbols.

⚙️ How the Game Works
The user enters the size of the field.
The field is initialized with empty spaces.
Players A and B take turns automatically.
On each turn, a player enters a position (1 to size) where they want to place an X.
The program checks:
whether the position is valid
whether the position is already occupied
After each move, the current state of the field is displayed.
The game ends when three X symbols appear consecutively.
🧠 Game Rules
Players alternate turns (A → B → A → B ...).
Each field position can contain only one X.
The player who first creates 3 consecutive X symbols wins.
🧩 Program Functions
main()
Controls the game flow
Handles user input and player turns
draw(char field[], int size)
Displays the current state of the field
addCross(char field[], int size, int position)
Places an X at the selected position
Validates input and checks if the position is already occupied
isSolved(char field[], int size)
Checks whether there are 3 consecutive X symbols in the field
🚨 Possible Improvements
Fix input validation (position < 1 || position > size should be enforced correctly)
Add handling for non-numeric input
Allow undo or reset functionality
Improve visuals (e.g., use different symbols for players A and B like X and O)
Add a simple AI opponent
🖥️ Example Gameplay
Enter the size of field: 5

 1 2 3 4 5
+-+-+-+-+-+
| | | | | |
+-+-+-+-+-+

Player A: 2
Player B: 3
Player A: 4
...
