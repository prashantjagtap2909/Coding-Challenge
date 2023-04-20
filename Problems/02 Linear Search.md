#### Problem 02:  Linear Search

This is linear search algorithm that searches for an integer value X in an integer array arr of size N. The function returns the index of the first occurrence of X in the array arr, or -1 if X is not present in the array.
![image](https://user-images.githubusercontent.com/93985255/233403880-c69585b1-9e05-400b-9915-3ea66d69c682.png)

- The function starts by iterating through each element of the array arr using a for loop, with the loop variable i starting from 0 and ending at N-1. For each element of the array arr[i], the code checks if it is equal to the search value X using the == operator.
- If arr[i] is equal to X, then the function immediately returns the index i. This is because we want to find the first occurrence of the search value, and the loop starts from the beginning of the array.
- If the search value is found at index i, then there is no need to search the rest of the array as we are only interested in the first occurrence.
- If the search value is not found in the entire array, then the function returns -1. This indicates that the search value is not present in the array arr.
