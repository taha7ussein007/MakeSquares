# MakeSquares (Advanced)
Make a square with size 5X5 by using 4 or 5 pieces. The pieces can be rotated or flipped and all pieces should be used to form a square. Example set of pieces.
![alt text](https://github.com/taha7ussein007/MakeSquares/blob/master/1.PNG)
There may be more than one possible solution for a set of pieces, and not every arrangement will work even with a set for which a solution can be found. Examples using the above set of pieces…
Rotate piece D 90 degree then flip horizontal {R 90 + F H}
![alt text](https://github.com/taha7ussein007/MakeSquares/blob/master/2.PNG)
Input:
The first line contains number of pieces. Each piece is then specified by listing a single line with two integers, the number of rows and columns in the piece, followed by one or more lines which specify the shape of the piece. The shape specification consists of 0 or 1characters, with the 1 character indicating the solid shape of the puzzle (the 0 characters are merely placeholders). For example, piece A above would be specified as follows:
2 3
111
101
Output:
Your program should report all solution, in the format shown by the examples below. A 4-row by 4-column square should be created, with each piece occupying its location in the solution. The solid portions of piece #1 should be replaced with `1' characters, of piece #2 with `2' characters. Last line displays the pieces which are changed in the original form. If the piece rotate with angle 90{R 90}, and flip vertical or horizontal {F V or F H}. For cases which have no possible solution simply report "No solution possible".
