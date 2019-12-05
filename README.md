# AlfaGeir - Chess Bot

## About
This is a school project which is written mainly to test out the AI algorithms. This chess bot uses a decision-tree solution with min-max  and alpha-beta pruning algorithm. 

## Dependencies To run the program you need to have [PyGame](https://www.pygame.org/) installed. 
To install PyGame run:

    python3 -m pip install -U pygame --user


The program also uses a [python chess](https://python-chess.readthedocs.io/en/v0.28.0/index.html) library for board representation and move validation. 
To install python-chess run:

    pip3 install python-chess

## To Run
To run the program navigate to the repo and do:

~~~
python3 chessboard.py
~~~

## Game Modes
At the start of the program you will get a few options in the terminal where you can chose between:
1. player vs AI
2. AI vs AI
3. player vs player

To chose a mode you have to write the corresponding number in the terminal.

To move a piece, click chosen piece and then click the square you want to move the piece to. If it is not a legal move, it will be ignored and you'll have to try again.

GL & HF
