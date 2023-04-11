# Tic-Tac-Toe Game
This is a simple Tic-Tac-Toe game built using ReactJS. The game has two players - Player 1 (O) and Player 2 (X). The game ends when either of the players manages to get three of their marks in a row (horizontally, vertically, or diagonally) or when the board is completely filled without a winner.

## How to Play
The game begins with Player 1 (O) making the first move.
Players take turns making moves until either one player wins or the game ends in a tie.
To make a move, click on an empty box on the board.
To restart the game, click the "Restart" button.
Code Structure
The code is divided into four main components - App, Board, Box, and ScoreBoard.

## App
The App component serves as the main container for the game. It maintains the state of the game, handles player moves, checks for a winner, and resets the game.

### Board
The Board component represents the game board. It receives the current state of the game as props from the App component and renders the board accordingly.

### Box
The Box component represents an individual box on the board. It receives the value of the box ('X', 'O', or null) and a function to handle click events as props from the Board component.

### ScoreBoard
The ScoreBoard component displays the current score of each player.

## Running the Game
To run the game:

Clone the repository to your local machine.
Navigate to the root directory of the project.
Install the dependencies by running npm install.
Start the development server by running npm start.
Open http://localhost:3000 in your web browser to play the game.
