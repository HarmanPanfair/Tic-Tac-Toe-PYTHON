# Tic-Tac-Toe-Python
Tic Tac Toe game using Jupyter Notebook
Create a Tic Tac Toe game

Here are the requirements:

2 players should be able to play the game (both sitting at the same computer)
The board should be printed out every time a player makes a move
You should be able to accept input of the player position and then place a symbol on the board

Below is a set of steps for you to follow to try to create the Tic Tac Toegame!

To take input from a user:

player1 = input("Please pick a marker 'X' or 'O'")
Note that input() takes in a string. If you need an integer value, use

position = int(input('Please enter a number'))

To clear the screen between moves:

from IPython.display import clear_output
clear_output()
Note that clear_output() will only work in jupyter. To clear the screen in other IDEs, consider:

print('\n'*100)
This scrolls the previous board up out of view. Now on to the program
