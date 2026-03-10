The project was developed using Python 3.10.10 using visual studio code. This program is a command-line implementation of the classic game Tic-Tac-Toe.

The game starts by asking the user to choose their marker - 'X' or 'O'. Then, the game checks if the user wants to start playing or not. If they do, the game starts with an empty board. The game alternates between the human player and the computer. When it is the human's turn, they choose a position on the board to place their marker. The computer's choice is made using the minimax algorithm. The game ends when either the human or the computer wins or when the board is full. The player is then asked if they want to play again. The minimax algorithm is used to determine the best move for the computer by recursively calculating the best score for all possible moves until the end of the game. The score is determined as follows:

• If the computer wins, the score is 10.<br />
• If the human wins, the score is -10.<br />
• If it is a tie, the score is 0.<br />

The algorithm assumes that the human player always plays optimally.
