# Tic-Tac-Toe-game-
# Internpe project 

This code is a Python script for playing a simple game of Tic-Tac-Toe. 

print_board(board): This function takes a 3x3 board as input and prints it to the console, formatting it to resemble a Tic-Tac-Toe grid.

check_winner(board): This function checks the current state of the board to see if there's a winner. It checks for three in a row horizontally, vertically, and diagonally. If there's a winner, it returns the winning player ('X' or 'O'), otherwise, it returns None.

is_board_full(board): This function checks if the board is full, meaning there are no empty spaces left. If the board is full, it returns True; otherwise, it returns False.

play_game(): This is the main function that orchestrates the game. It initializes an empty board, sets the starting player to 'X', and then enters a loop where players take turns entering their moves. It alternates between 'X' and 'O' players until there's a winner or a draw.

In the main block (if __name__ == "__main__":), the play_game() function is called to start the game when the script is run as the main program.

Overall, this script provides a basic implementation of the Tic-Tac-Toe game in Python, allowing two players to take turns making moves until there's a winner or a draw.
