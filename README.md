# AlfaGeir - Chess Bot

## About
This is a chess AI that uses decision-tree solution with min-max algorithm and alpha-beta pruning algorithm. This is a school project which is written mainly to test out the AI algorithms.

## To Run
To run the program you need to have [PyGame](https://www.pygame.org/) installed. 
To install PyGame run:

    python3 -m pip install -U pygame --user


The program also uses a [python chess](https://python-chess.readthedocs.io/en/v0.28.0/index.html) library for board representation and move validation. 
To install python-chess run:

    pip3 install python-chess

To run the program go into the repo and do:

~~~
python3 chessboard.py
~~~

## Game Modes
At the start of the program you will get a few options in the terminal where you can chose between:
1. player vs AI
2. AI vs AI
3. player vs player

To chose a mode you have to write the corresponding number in the terminal

To move a piece, you press its square, and then the square you want to move the piece to. If it is a legal move it will do the move, and if not, it will ignore the move request.
