#### Problem 03:  Transpose of Matrix


  - The function takes two arguments: the matrix (as a reference to a vector of vectors of integers) and the size of the matrix (which is assumed to be n x n).

![image](https://user-images.githubusercontent.com/93985255/233677486-d962a082-6c3e-4b47-b7ef-7ee5badcfe49.png)

 - The outer loop iterates over the rows of the matrix (i.e., from 0 to n-1).
The inner loop iterates over the columns of the matrix (i.e., from i+1 to n-1). By starting at i+1, the function only iterates over the upper triangle of the matrix, excluding the diagonal.

 - Inside the inner loop, the swap function is used to exchange the elements at (i, j) and (j, i), which gives the transpose of the matrix.

