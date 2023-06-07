### Problem 13 - BFS of Graph


- The function bfsOfGraph takes two parameters: V (the number of vertices in the graph) and adj[] (an array of vectors representing the adjacency list of the graph).
![image](https://github.com/prashantjagtap2909/Coding-Challenge/assets/93985255/db9210de-fa40-4460-9359-38e512e17fa7)


- Two empty vectors are initialized: res (which will store the BFS traversal order) and vis (which will keep track of visited vertices). res will be returned as the result.

- A queue q is created to store the vertices to be processed during the BFS traversal.

- The first vertex (vertex 0) is added to the queue and marked as visited (vis[0] = 1).

- The BFS traversal begins with a loop that continues until the queue becomes empty.

- In each iteration of the loop, the front vertex (node) is removed from the queue using q.front() and q.pop().

- The current vertex (node) is added to the res vector to store the BFS traversal order.

- For each adjacent vertex it of the current vertex (node), the following steps are performed:

- If the adjacent vertex it has not been visited (!vis[it]), it is added to the queue using q.push(it) and marked as visited (vis[it] = 1).
- After the BFS traversal is complete, the res vector containing the BFS traversal order is returned.
