# Algorithm for Tic Tac Toe Game Using C++

## Objective
To implement a console-based Tic Tac Toe game in C++ that allows two players to play alternately and determines the game result correctly.

## Algorithm Steps

1. Initialize a character array of size 9 to represent the game board.
2. Assign Player X as the starting player.
3. Display the current state of the board.
4. Prompt the current player to enter a position between 1 and 9.
5. Validate the input:
   - The position must be within the valid range.
   - The selected position must not already be occupied.
6. Update the board with the current player's symbol.
7. Check for a winning condition by comparing:
   - All rows
   - All columns
   - Both diagonals
8. If a winning condition is satisfied:
   - Display the final board.
   - Declare the current player as the winner.
   - Terminate the game.
9. If all positions are filled and no player has won:
   - Declare the game as a draw.
   - Terminate the game.
10. Switch the current player.
11. Repeat steps 3 to 10 until the game ends.

## Data Structures Used
- Character array to store the game board.

## Time Complexity
- Constant time per move.
- Overall time complexity is constant due to fixed board size.

## Space Complexity
- Constant space usage.
