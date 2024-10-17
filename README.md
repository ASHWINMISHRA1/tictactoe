# Project Title : <Name of the Project>
# TicTacToe
#### Student Name : <Ashwinikumar Mishra>      
#### Class : D6AD-B
#### Roll No : 64
## Link to the Github Repo : <>
## Description of the Game : The Tic-Tac-Toe game is a 2-player game where players take turns marking the spaces in a 3x3 grid with either an "X" or an "O". The player who succeeds in placing three respective marks in a horizontal, vertical, or diagonal row wins the game. If all nine spaces are filled without a winner, the game results in a tie.
## Data Structures Used :
- DS 1 : Purpose
 *Used to store the buttons on the grid.*
Each button corresponds to a cell in the 3x3 game board. The array helps assign and retrieve buttons to allow UI operations (like enabling, disabling, or updating text).
- DS 2 : Purpose-
*Represents the game state.*
Each position in the array stores the current mark ("X" or "O") for a specific cell. This structure allows easy checks for winning conditions (rows, columns, and diagonals).
## Logic of the Game :
1.Player Turns:

The game starts with player X by default.
Players alternate turns, and the current button pressed is updated with "X" or "O". The xTurn boolean keeps track of whose turn it is.

2. Button State Management:

When a button is pressed, it gets disabled to avoid duplicate inputs.
The state of the board (board[][]) is updated to reflect the player’s choice.
Winner Check:

3. After each move, the game checks:

If a player has won by completing a row, column, or diagonal with the same mark.
If all cells are filled and no one has won, the game declares a tie.
The game uses loops and conditions to efficiently evaluate the 3x3 grid for these outcomes.

4. Game Reset:

If a player wins or the game ends in a tie, the board and button states are reset for a new game.

## Program
- Complete Program
## Output
 winning Screenshot 1
![image](https://github.com/user-attachments/assets/68c8a297-d0cc-4dff-a694-656d4f408570)
- Failure Screenshot 2
  ![image](https://github.com/user-attachments/assets/06a9b7d1-fb45-4f46-9bf8-5e0dcd84172a)

## Conclusion : This Tic-Tac-Toe game demonstrates the use of Java Swing for graphical interfaces and employs 2D arrays for managing the game state and UI components. The logic is simple yet effective, with checks for winning conditions and tie scenarios. The project showcases basic event handling and game design using object-oriented principles, making it a great starting point for learning Java GUI programming.
