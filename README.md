# Sudoku


For this round, the program doesn't need to display the game, persist anything, generate a solvable starting point, or solve a game. It only needs to model in memory the state of a game that's being played by a human player.

Suppose that the board background is black. The game starts with some cells filled in with digits which are green, since we know they're correct. The player adds digits through some UI that we're not going to worry about. If a digit is obviously incorrect (i.e. the same digit is already in the same row, column or 3x3 square), the game displays it in red. If a digit is not obviously incorrect the game displays it in white.

Your task is to write a model object which has methods for placing a known-correct digit on the board (used by the game to set up the board), placing a not-necessarily-correct digit on the board (used by the player to play the game), and for querying the state of a location on the board (digit, if any, and color).

Please write your code using TDD. Use any language and test framework
