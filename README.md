# Gomoku Game

![gomoku](https://github.com/user-attachments/assets/ad1003c1-4397-4234-97a8-b5fd64cff914)

## Objective

The objective of Gomoku is to be the first player to form a consecutive chain of five symbols horizontally, vertically, or diagonally on the board.


![win](https://github.com/user-attachments/assets/3b14c345-484b-4b44-b3c6-d248d77f4141)

![winsO](https://github.com/user-attachments/assets/386b902a-2de4-4dbf-9d17-b30c0a837aa7)


## Game Setup

- **Board**: Gomoku is traditionally played on a 15x15 grid.
- **Players**: The game is played between two players, in my version it's human vs AI.
- **Symbols**: The human player uses X's, and the AI uses O's.
- **Score**: Each time the human or the AI wins, the score is updated. It starts with 0-0.
- **Reset Button**: Any time the button is pressed, the board is reverted to its start-up state.
  
![first_state](https://github.com/user-attachments/assets/40def683-9244-4a60-a94f-e1c22409c3dd)


## Game Rules

1. **Starting the Game**:  
   - The game begins with an empty board. 
   - The human player takes the first turn, placing its symbol(X) somewhere on the table.

2. **Taking Turns**:  
   - Players alternate turns, AI will place its symbol(O) somewhere on an empty place. 
   - AI places randomly until the human will have 4 in a line, then it will try to block the human in an attempt to stop the forthcoming loss.
   - If the AI has 4 in a line, it will prioritize placing the 5th symbol and win the game.

3. **Winning the Game**:  
   - A player wins by being the first to align five consecutive symbols horizontally, vertically, or diagonally.
   - If the board fills up without either player forming a chain of five stones, the game is a draw.

4. **No Removal**:  
   - Once a symbol is placed on the board, it cannot be moved or removed during the game.
     
![image](https://github.com/user-attachments/assets/3c0e9781-63aa-44ba-8533-14929dc90df2)
![image](https://github.com/user-attachments/assets/188f7705-0991-4932-981f-7230bbd81d97)
![image](https://github.com/user-attachments/assets/c6e0534c-263c-4b56-ad3c-a9ac0e5a84e1)
![image](https://github.com/user-attachments/assets/029f4b13-31ef-48fd-9a4e-532b5d1793cf)
![image](https://github.com/user-attachments/assets/7459cb64-953f-4a64-9b95-413798139872)

## Functionalities

- **98% Test Coverage with PyUnit**:  
  Most of the Gomoku game has been rigorously tested using PyUnit, achieving 98% code coverage. This ensures that almost every function and possible game scenario has been accounted for, providing a robust and reliable game experience.
  
  ![image](https://github.com/user-attachments/assets/eecac49d-c12a-472a-8d45-6caf09c10e47)

- **User Interface (UI)**:  
  In addition to a graphical user interface (GUI), the game also offers a command-line-based user interface (UI). This allows users to play the game in a terminal environment, depending on the preference.

  ![image](https://github.com/user-attachments/assets/47e6d2dc-3494-4dfe-b29b-2cb9cae743e9)
