# ChessBot
Lets create a Chess bot to read  chess board and suggest moves, Shell we ?

Creating a program that can read a chessboard from an image and suggest moves.

Here's a high-level outline :
Image Recognition:
1. Use library  OpenCV to process the image
2. Detect squares and pieces.
3. Convert the visual board into a data structure
4. Integrate a chess engine (like Stockfish, for example) into Python program
5. Use kinter or Pygame to display the board and interact with the user


import chess
import chess.svg
import chess.engine
