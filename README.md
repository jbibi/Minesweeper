# Minesweeper
Minesweeper Game in Javascript

This is a Minesweeper game that runs from the terminal. The code of the game contains ES6 elements that were converted to ES5 with Babel. When making a move the number selected to flip a tile to check for bombs must be done as an array.


INSTRUCTIONS

To play Minesweeper, we will create instances of MineSweeperGame in command line.
For example:
In the command line, navigate to the lib directory and run `node`
Run `.load game.js` to load the contents of this file.
Then create a Game instance and run commands like so:
let game = new Game(3, 3, 3);
game.playMove(0, 1);
game.playMove(1, 2);
When done run `.exit
