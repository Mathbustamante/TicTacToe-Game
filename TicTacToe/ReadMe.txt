Matheus Bustamante Lab 3

1. No errors nor warning were encountered when building the program.

In my program, any letter, out of bouce index, and putting a piece on top of the other is 
considered a bad input. When this happens it will ask you to try one more time unless the
user quit the game which will quit the program. I put all the bad input examples
bellow as well as some games where player X, O won and a draw.

2. RNNING THE PROGRAM:

#ONE ARGUMENT:
H:\332\labs\lab3\Lab3\Debug>Lab3.exe
How to use this program: Lab3.exe TicTacToe

#TWO ARGUMENTS: (Wrong argument name)
H:\332\labs\lab3\Lab3\Debug>Lab3.exe TicTow
How to use this program: Lab3.exe TicTacToe

#THREE ARGUMENTS:
H:\332\labs\lab3\Lab3\Debug>Lab3.exe TicTacToe THREE
How to use this program: Lab3.exe TicTacToe

#CORRECT ARGUMENTS:
H:\332\labs\lab3\Lab3\Debug>Lab3.exe TicTacToe
4
3
2
1
0
 0 1 2 3 4

Player O, enter the location of your piece (x, y):

Prints the empty board and a message for payer O to input the coordinate.

#PLAYING THE GAME WITH VALID AND INVALID INPUTS (QUIT THE GAME):

Player O, enter the location of your piece (x, y): 1,1
4
3
2
1  O
0
 0 1 2 3 4

Player O:  (1,1);

Player X, enter the location of your piece (x, y): 2,2

4
3
2    X
1  O
0
 0 1 2 3 4

Player X:  (2,2);

Player O, enter the location of your piece (x, y): 3,3
4
3      O
2    X
1  O
0
 0 1 2 3 4

Player O:  (3,3); (1,1);

Player X, enter the location of your piece (x, y): 2,2
You cannot put a piece on top of the other. Try again: 2,3

4
3    X O
2    X
1  O
0
 0 1 2 3 4

Player X:  (2,3); (2,2);

Player O, enter the location of your piece (x, y): asdasd
Please enter a valid input (x, y). Try Again: 1,e
Please enter a valid input (x, y). Try Again: 1,3
4
3  O X O
2    X
1  O
0
 0 1 2 3 4

Player O:  (1,3); (3,3); (1,1);

Player X, enter the location of your piece (x, y): quit
User quit the game

#PLAYING THE GAME WITH VALID AND INVALID INPUTS (O WON THE GAME):

H:\332\labs\lab3\Lab3\Debug>Lab3.exe TicTacToe
4
3
2
1
0
 0 1 2 3 4


Player O, enter the location of your piece (x, y): 1,1
4
3
2
1  O
0
 0 1 2 3 4

Player O:  (1,1);

Player X, enter the location of your piece (x, y): 2,2

4
3
2    X
1  O
0
 0 1 2 3 4

Player X:  (2,2);

Player O, enter the location of your piece (x, y): 2,3
4
3    O
2    X
1  O
0
 0 1 2 3 4

Player O:  (2,3); (1,1);

Player X, enter the location of your piece (x, y): 3,3

4
3    O X
2    X
1  O
0
 0 1 2 3 4

Player X:  (3,3); (2,2);

Player O, enter the location of your piece (x, y): abc
Please enter a valid input (x, y). Try Again: 1,1
You cannot put a piece on top of the other. Try again: 1,3
4
3  O O X
2    X
1  O
0
 0 1 2 3 4

Player O:  (1,3); (2,3); (1,1);

Player X, enter the location of your piece (x, y): 3,2

4
3  O O X
2    X X
1  O
0
 0 1 2 3 4

Player X:  (3,3); (2,2); (3,2);

Player O, enter the location of your piece (x, y): 1,2
4
3  O O X
2  O X X
1  O
0
 0 1 2 3 4

Player O:  (1,3); (2,3); (1,2); (1,1);
Player O won the game! Congrats!!


#PLAYING THE GAME WITH VALID AND INVALID INPUTS (DRAW):
H:\332\labs\lab3\Lab3\Debug>Lab3.exe TicTacToe
4
3
2
1
0
 0 1 2 3 4


Player O, enter the location of your piece (x, y): 1,1
4
3
2
1  O
0
 0 1 2 3 4

Player O:  (1,1);

Player X, enter the location of your piece (x, y): 3,3

4
3      X
2
1  O
0
 0 1 2 3 4

Player X:  (3,3);

Player O, enter the location of your piece (x, y): 2,2
4
3      X
2    O
1  O
0
 0 1 2 3 4

Player O:  (2,2); (1,1);

Player X, enter the location of your piece (x, y): 2,3

4
3    X X
2    O
1  O
0
 0 1 2 3 4

Player X:  (2,3); (3,3);

Player O, enter the location of your piece (x, y): 1,3
4
3  O X X
2    O
1  O
0
 0 1 2 3 4

Player O:  (1,3); (2,2); (1,1);

Player X, enter the location of your piece (x, y): 1,2

4
3  O X X
2  X O
1  O
0
 0 1 2 3 4

Player X:  (2,3); (3,3); (1,2);

Player O, enter the location of your piece (x, y): 3,2
4
3  O X X
2  X O O
1  O
0
 0 1 2 3 4

Player O:  (1,3); (2,2); (3,2); (1,1);

Player X, enter the location of your piece (x, y): 3,1

4
3  O X X
2  X O O
1  O   X
0
 0 1 2 3 4

Player X:  (2,3); (3,3); (1,2); (3,1);

Player O, enter the location of your piece (x, y): 2,1
4
3  O X X
2  X O O
1  O O X
0
 0 1 2 3 4

Player O:  (1,3); (2,2); (3,2); (1,1); (2,1);
We have a draw

#PLAYING THE GAME WITH VALID AND INVALID INPUTS (X WON THE GAME):
H:\332\labs\lab3\Lab3\Debug>Lab3.exe TicTacToe
4
3
2
1
0
 0 1 2 3 4


Player O, enter the location of your piece (x, y): 1,1
4
3
2
1  O
0
 0 1 2 3 4

Player O:  (1,1);

Player X, enter the location of your piece (x, y): 1,1
You cannot put a piece on top of the other. Try again: 1,1
You cannot put a piece on top of the other. Try again: 1,a
You cannot put a piece on top of the other. Try again: 2,2

4
3
2    X
1  O
0
 0 1 2 3 4

Player X:  (2,2);

Player O, enter the location of your piece (x, y): quit
User quit the game
H:\332\labs\lab3\Lab3\Debug>Lab3.exe TicTacToe
4
3
2
1
0
 0 1 2 3 4


Player O, enter the location of your piece (x, y): 1,1
4
3
2
1  O
0
 0 1 2 3 4

Player O:  (1,1);

Player X, enter the location of your piece (x, y): 1,1
You cannot put a piece on top of the other. Try again: 2,2

4
3
2    X
1  O
0
 0 1 2 3 4

Player X:  (2,2);

Player O, enter the location of your piece (x, y): 3,3
4
3      O
2    X
1  O
0
 0 1 2 3 4

Player O:  (3,3); (1,1);

Player X, enter the location of your piece (x, y): 2,3

4
3    X O
2    X
1  O
0
 0 1 2 3 4

Player X:  (2,3); (2,2);

Player O, enter the location of your piece (x, y): 1,3
4
3  O X O
2    X
1  O
0
 0 1 2 3 4

Player O:  (1,3); (3,3); (1,1);

Player X, enter the location of your piece (x, y): 1,2

4
3  O X O
2  X X
1  O
0
 0 1 2 3 4

Player X:  (2,3); (1,2); (2,2);

Player O, enter the location of your piece (x, y): 1,a
Please enter a valid input (x, y). Try Again: asdasd
Please enter a valid input (x, y). Try Again: 3,2
4
3  O X O
2  X X O
1  O
0
 0 1 2 3 4

Player O:  (1,3); (3,3); (3,2); (1,1);

Player X, enter the location of your piece (x, y): 2,1

4
3  O X O
2  X X O
1  O X
0
 0 1 2 3 4

Player X:  (2,3); (1,2); (2,2); (2,1);
Player X won the game! Congrats!!

#INPUTS OUT OF BOUNDS EXAMPLE
H:\332\labs\lab3\Lab3\Debug>Lab3.exe TicTacToe
4
3
2
1
0
 0 1 2 3 4


Player O, enter the location of your piece (x, y): 1,1
4
3
2
1  O
0
 0 1 2 3 4

Player O:  (1,1);

Player X, enter the location of your piece (x, y): 2,2

4
3
2    X
1  O
0
 0 1 2 3 4

Player X:  (2,2);

Player O, enter the location of your piece (x, y): 3,3
4
3      O
2    X
1  O
0
 0 1 2 3 4

Player O:  (3,3); (1,1);

Player X, enter the location of your piece (x, y): 4,4
Please enter a valid input (x, y). Try Again: 3,5
Please enter a valid input (x, y). Try Again: 2,2
You cannot put a piece on top of the other. Try again: 1,2

4
3      O
2  X X
1  O
0
 0 1 2 3 4
