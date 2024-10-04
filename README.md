# Tic Tac Toe Game

This is a simple command-line implementation of the classic Tic Tac Toe game in Java.

## Description

The Tic Tac Toe game is a two-player game where players take turns placing their respective symbols (X or O) on a 3x3 grid. The objective is to get three of their symbols in a horizontal, vertical, or diagonal row. This implementation allows two players to play the game on the command line interface, with features such as detecting winning conditions, tie games, and the option to play again after each game.

## Features

- Two-player mode
- Command-line interface for input and output
- 3x3 game board
- Detect winning conditions (rows, columns, diagonals)
- Detect tie games
- Option to play again after each game

## How to Run

1. Ensure you have Java installed on your system.
2. Clone or download this repository to your local machine.
3. Navigate to the project directory using the terminal or command prompt.
4. Compile the Java file: `javac Main.java`
5. Run the compiled program: `java Main`

## Gameplay

1. The game will display the initial empty game board.
2. Player X will be prompted to enter a row (0-2) and column (0-2) to make their move.
3. After a valid move, the game board will be updated, and Player O will be prompted to make their move.
4. Players will take turns making moves until a winner is determined or the game ends in a tie.
5. If a player gets three of their symbols in a row (horizontally, vertically, or diagonally), they win the game.
6. If all cells are filled without a winner, the game is declared a tie.
7. After each game, the players will be prompted to play again or exit the program.

## Code Structure

The code consists of a single Java class named `Main` with the following methods:

- `main`: Entry point of the program, initializes the game board, and handles the game loop.
- `initializeBoard`: Initializes the game board with empty cells ('-').
- `displayBoard`: Prints the current state of the game board.
- `makeMove`: Prompts the current player for a move and updates the game board.
- `isValidMove`: Checks if a player's move is valid.
- `checkGameStatus`: Checks for winning conditions or a tie game.
- `declareWinner`: Prints the winner's symbol and declares the winner.
- `declareTie`: Prints a message for a tie game.
- `playAgainPrompt`: Prompts the players to decide if they want to play another game.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please contact me via github!

## License

This project is licensed under Sai Ravuri, student at CPP. 
