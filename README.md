# red
red is a CLI-based chess engine which uses a combination of alpha-beta pruning and transpositions to search for the best move.
It can be run in your local terminal using a command of four characters: a1b3; the first two of which represents the position of piece you want to move, and the other two the position where you want to move it to. 
The GUI of red is yet to be made. Adding to that, it only declares a winner when the opponent king is captured.  This is equivalent to checkmate except for the cases of stalemate. Stalemates are separately considered while evaluating the position of the board. It has a lot of scope of improvement when combined with ML algorithms as well.

It's capable of defeating chess bots rated as high as 1500 on chess.com. However, it couldn't defeat Isabel (rated 1600). A GIF of the game between the two would is present on the project homepage. 
