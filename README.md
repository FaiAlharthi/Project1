# Project1
Tic-Tac-Toe

features:
- choose to play with X or O
- choose to play 1 Round or 3 Rounds

methods:
- checkWinner : checking if there's a winner
- isAvailable : check if the field is empty, and if the chosen index is correct
- isLegal : returns true if the user chose a valid char ( X or O )
- displayGrid : print the Game Board
- resetGrid : returns the grid to it's default values for new round
- filledWith : returns a char for a specific field
- addToGrid : add new char to the grid

constraints:
- no characters is valid other than X or O
- no positions valid except 1 to 9

