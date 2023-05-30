# connect-4.c
HOW TO PLAY:
The game is a two player game, where each player has to connect four pieces of the same color in a row, column or diagonal.

At first, you will be prompted to insert the players' names, and each player will be assigned a symbol (X or O).

For each turn the play board will be displayed, and the player will be prompted to insert the column where he wants to place his piece.

The game will end when one of the players connects four pieces in a row, column or diagonal, or when the board is full.


This code implements the game of Connect Four in C. Let's go through the output of the code:

                                                                  Example output
                                             *******************************************************
                                                    *** WELCOME TO STEFAN'S CONNECT FOUR! ***
                                             *******************************************************
Enter the players' names, or type 'C' or 'L'.
Name of player 1: Stefan
Name of player 2: c
Okay, let's play!
|1|2|3|4|5|6|7|
+-+-+-+-+-+-+-+
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
Stefan (X): Which column to select? 4
|1|2|3|4|5|6|7|
+-+-+-+-+-+-+-+
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | |X| | | |
Computer (O) is thinking... and selected column 1.
|1|2|3|4|5|6|7|
+-+-+-+-+-+-+-+
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
|O| | |X| | | |
Stefan (X): Which column to select? 9
Invalid input. Try again!
Stefan (X): Which column to select? 5
Page 10 of 10
|1|2|3|4|5|6|7|
+-+-+-+-+-+-+-+
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
|O| | |X|X| | |
Computer (O) is thinking... and selected column 3.
|1|2|3|4|5|6|7|
+-+-+-+-+-+-+-+
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
|O| |O|X|X| | |
Stefan (X): Which column to select? s
The game has been saved to a file.
Stefan (X): Which column to select? 2
|1|2|3|4|5|6|7|
+-+-+-+-+-+-+-+
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
|O|X|O|X|X| | |
Computer (O) is thinking... and selected column 6.
|1|2|3|4|5|6|7|
+-+-+-+-+-+-+-+
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
|O|X|O|X|X|O| |
[. . . A COUPLE OF MOVES LATER . . .]
Stefan (X): Which column to select? 2
|1|2|3|4|5|6|7|
+-+-+-+-+-+-+-+
| | | | | | | |
| | | | | | | |
| | | | |O| | |
| |X|O|O|X| | |
| |X|O|X|X| | |
|O|X|O|X|X|O| |
Computer (O) is thinking... and selected column 3.
|1|2|3|4|5|6|7|
+-+-+-+-+-+-+-+
| | | | | | | |
| | | | | | | |
| | |O| |O| | |
| |X|O|O|X| | |
| |X|O|X|X| | |
|O|X|O|X|X|O| |
Computer (O) has won!
