# DAA_Fall_2021
Std name = Muhammad Fasih Rohan

Std ID= 62725

Website = https://n-queenpro.web.app/


Hi this is Fasih Rohan...currently enrolled in a BS program in Computer Science.Here we are studying Design amd Analysis of Algorithms.In this, we are getting know how an algorithms works and what are beneficial oints in our software.

The n-queens problem is to determine Q(n),the number of different ways in which n queensmay be placed on an n x n chessboard so that
no two queens are on the same row, column ordiagonal.
The above condition will satisfy the fact that queen can move horizontally and vertically so 1 a queen is placed in a row no other queen can be placed in that row. Same for the coloumn applies.

Squres blocked by the queen is minimum if it is placed in four corner ( also if in side ) as only 1 diagonal is involved.( in side 2 diagonal is involved and it complicates the situation)

Now we have to place 1queen in 1row each

Now place 1st queen in 1st row but in such a way that it will block least other squares but don't place it in corners. Reserve the corners for latter as it blocks minimum squares.

after placing queen in 1st 4 rows stop.and leave the 5 th row and now start from last row .

The reason for this is that now u will have to adjust the position think and place the queen and u can't adjust only in last row .

So follow the instructions.

now you will have 3 choices to place queen in last row. Hold the queen in any 2 places you will find that only when you place queen in particular position than only you will have option for last 2nd and 3rd row . hit that positions.

Now only one box will be left and it will be in 4th row.

References: 

https://www.quora.com/What-is-the-best-algorithm-for-solving-n-queen-problems

https://www.youtube.com/watch?v=pnLFu0yJzN8

These links may not to the point but I just take helps out of these to learn N-Queen problem.



