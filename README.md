Problem
Vestigium means "trace" in Latin. In this problem we work with Latin squares and matrix traces.
The trace of a square matrix is the sum of the values on the main diagonal (which runs from the upper left to the lower right).
An N-by-N square matrix is a Latin square if each cell contains one of N different values, and no value is repeated within a row or a column. In this problem, we will deal only with "natural Latin squares" in which the N values are the integers between 1 and N.
Given a matrix that contains only integers between 1 and N, we want to compute its trace and check whether it is a natural Latin square. To give some additional information, instead of simply telling us whether the matrix is a natural Latin square or not, please compute the number of rows and the number of columns that contain repeated values.

Sample

Input
3
4
1 2 3 4
2 1 4 3
3 4 1 2
4 3 2 1
4
2 2 2 2
2 3 2 3                                                                                        
2 2 2 3
2 2 2 2
3
2 1 3
1 3 2
1 2 3

Output
Case #1: 4 0 0
Case #2: 9 4 4
Case #3: 8 0 2

  
In Sample Case #1, the input is a natural Latin square, which means no row or column has repeated elements. All four values in the main diagonal are 1, and so the trace (their sum) is 4.

In Sample Case #2, all rows and columns have repeated elements. Notice that each row or column with repeated elements is counted only once regardless of the number of elements that are repeated or how often they are repeated within the row or column. In addition, notice that some integers in the range 1 through N may be absent from the input.

In Sample Case #3, the leftmost and rightmost columns have repeated elements.



Test case: (just copy and paste)

20
5
1 2 3 4 5
2 6 6 3 6
3 3 3 3 3
4 3 2 1 6
5 6 8 4 2
6
2 2 2 2 4 5
2 3 3 2 7 8
2 3 3 2 7 5
2 2 2 2 2 3
4 8 6 9 7 5
7 5 8 6 4 2
4
1 2 3 4
2 1 4 3
3 4 1 2
4 3 2 1
4
2 2 2 2
2 3 2 3
2 2 2 3
2 2 2 2
3
2 1 3
1 3 2
1 2 3
5
1 2 3 4 5
2 6 6 3 6
3 3 3 3 3
4 3 2 1 6
5 6 8 4 2
6
2 2 2 2 4 5
2 3 3 2 7 8
2 3 3 2 7 5
2 2 2 2 2 3
4 8 6 9 7 5
7 5 8 6 4 2
4
1 2 3 4
2 1 4 3
3 4 1 2
4 3 2 1
4
2 2 2 2
2 3 2 3
2 2 2 3
2 2 2 2
3
2 1 3
1 3 2
1 2 3
5
1 2 3 4 5
2 6 6 3 6
3 3 3 3 3
4 3 2 1 6
5 6 8 4 2
6
2 2 2 2 4 5
2 3 3 2 7 8
2 3 3 2 7 5
2 2 2 2 2 3
4 8 6 9 7 5
7 5 8 6 4 2
4
1 2 3 4
2 1 4 3
3 4 1 2
4 3 2 1
4
2 2 2 2
2 3 2 3
2 2 2 3
2 2 2 2
3
2 1 3
1 3 2
1 2 3
5
1 2 3 4 5
2 6 6 3 6
3 3 3 3 3
4 3 2 1 6
5 6 8 4 2
6
2 2 2 2 4 5
2 3 3 2 7 8
2 3 3 2 7 5
2 2 2 2 2 3
4 8 6 9 7 5
7 5 8 6 4 2
4
1 2 3 4
2 1 4 3
3 4 1 2
4 3 2 1
4
2 2 2 2
2 3 2 3
2 2 2 3
2 2 2 2
3
2 1 3
1 3 2
1 2 3

all right reserved
