# AlfaGeir - Chess Bot

## About
This is a chess AI that uses decision-tree solution with min-max algorithm and alpha-beta pruning algorithm. This is a school project which is written mainly to test out the AI algorithms.

## To Run
To run the program you need to have pygame installed as it is what we uses to view the board. 
To install pygame run:

    python3 -m pip install -U pygame --user

The program also uses a chess library for representing the board and it also have move validation. 

To install python-chess run:

    pip3 install python-chess

To run the program do:

~~~
python3 chessboard.py
~~~

## Game Modes
At the start of the program you will get a few options in the terminal where you can chose between:
1. player vs AI
2. AI vs AI
3. player vs player

To chose a mode you have to write the corresponding number in the terminal

To move a piece you press it's square and then the square you want to move the piece to. If it is a legal move it will do the move, and if it's not a legal move it will ignore the move request.
