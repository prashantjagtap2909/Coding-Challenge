problem  10 : Print first n Fibonacci Numbers

- This code is an implementation of a function named printFibb that takes an integer n as an input parameter and returns a vector of type long long containing the first n numbers in the Fibonacci sequence.
- ![image](https://github.com/prashantjagtap2909/Coding-Challenge/assets/93985255/1c7d6824-b247-46fa-b7ef-0a188c26f280)

- The Fibonacci sequence is a series of numbers in which each number is the sum of the two preceding numbers, starting from 0 and 1. Therefore, the first two numbers in the sequence are always 0 and 1, and subsequent numbers are obtained by adding the previous two.
- The function initializes a vector v of size n with all elements initialized to zero. It then sets the first two elements of the vector to 1, as these are the first two numbers in the Fibonacci sequence.
- The function then enters a loop starting from the third element of the vector (index 2) up to the last element (index n-1).
- In each iteration of the loop, the value of the current element is set to the sum of the previous two elements, which is calculated by adding the value of the element at index i-1 and the value of the element at index i-2.
- Finally, the function returns the vector v containing the first n numbers in the Fibonacci sequence.
