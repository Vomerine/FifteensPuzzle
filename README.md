
# Fifteens puzzle

Every move has a cost of 1, and of course, since it is using A*, the program should find the optimal (lowest-cost) solution. In principle, there may be more than one optimal solution; the program is just expected to give one of these optimal solutions—it does not matter which one. The below shows some test cases with the expected input-output behavior. 0 represents the empty square. 


## Sample output
```
Finding solution for:
5 1 4 8 
7 0 2 11 
9 3 14 10 
6 13 15 12 

-------Start-------
Initial State:
5 1 4 8
7 0 2 11
9 3 14 10
6 13 15 12

Move 1:
5 1 4 8
7 3 2 11
9 0 14 10
6 13 15 12

Move 2:
5 1 4 8
7 3 2 11
9 14 0 10
6 13 15 12

Move 3:
5 1 4 8
7 3 2 11
9 14 10 0
6 13 15 12

Move 4:
5 1 4 8
7 3 2 0
9 14 10 11
6 13 15 12

Move 5:
5 1 4 0
7 3 2 8
9 14 10 11
6 13 15 12

Move 6:
5 1 0 4
7 3 2 8
9 14 10 11
6 13 15 12

Move 7:
5 1 2 4
7 3 0 8
9 14 10 11
6 13 15 12

Move 8:
5 1 2 4
7 0 3 8
9 14 10 11
6 13 15 12

Move 9:
5 1 2 4
0 7 3 8
9 14 10 11
6 13 15 12

Move 10:
5 1 2 4
9 7 3 8
0 14 10 11
6 13 15 12

Move 11:
5 1 2 4
9 7 3 8
6 14 10 11
0 13 15 12

Move 12:
5 1 2 4
9 7 3 8
6 14 10 11
13 0 15 12

Move 13:
5 1 2 4
9 7 3 8
6 0 10 11
13 14 15 12

Move 14:
5 1 2 4
9 7 3 8
0 6 10 11
13 14 15 12

Move 15:
5 1 2 4
0 7 3 8
9 6 10 11
13 14 15 12

Move 16:
0 1 2 4
5 7 3 8
9 6 10 11
13 14 15 12

Move 17:
1 0 2 4
5 7 3 8
9 6 10 11
13 14 15 12

Move 18:
1 2 0 4
5 7 3 8
9 6 10 11
13 14 15 12

Move 19:
1 2 3 4
5 7 0 8
9 6 10 11
13 14 15 12

Move 20:
1 2 3 4
5 0 7 8
9 6 10 11
13 14 15 12

Move 21:
1 2 3 4
5 6 7 8
9 0 10 11
13 14 15 12

Move 22:
1 2 3 4
5 6 7 8
9 10 0 11
13 14 15 12

Move 23:
1 2 3 4
5 6 7 8
9 10 11 0
13 14 15 12

Move 24:
1 2 3 4
5 6 7 8
9 10 11 12
13 14 15 0

Solution found!
-------END-------

Total # of moves: 24
```
