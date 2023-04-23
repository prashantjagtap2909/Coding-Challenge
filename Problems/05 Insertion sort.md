
#### Problem 05:  Insertion sort


 - The Insertion Sort algorithm works by iteratively comparing each element of the array with the elements before it and inserting the element at the correct position in the sorted part of the array.
  
 - The function takes an array arr and its size n as input arguments.

  - The outer loop of the function iterates over each element of the array arr except the last element (i.e., n-1) starting from index 0. The inner loop iterates from the next element (i.e., i+1) to the first element
  - Within the inner loop, the if statement checks if the current element at index j is smaller than its previous element at index j-1. If it is true, then it swaps the two elements by using a temporary variable temp.
  - This ensures that the smaller element is moved towards the beginning of the array, and the larger element is moved towards the end.

  - After the inner loop completes, the array is sorted up to the i+1th element. The outer loop continues the process until all elements are sorted.
 
