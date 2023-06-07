
### Problem 12: Inorder Traversal

- This is the in-order traversal of a binary tree which returns a vector of integers containing the values of the tree nodes in the in-order sequence.
- ![image](https://github.com/prashantjagtap2909/Coding-Challenge/assets/93985255/d689c41e-1860-4fb3-9ab8-453c7b7a604e)

- The function inOrder takes a pointer to a Node object as its parameter. Node seems to be a structure or class representing a node in a binary tree.

- It declares a vector of integers named res to store the values of the nodes in the in-order sequence.
- The first conditional statement checks if the root is not NULL, which means there is a node in the tree.

- Inside the conditional statement, the inOrder function is recursively called on the left child of the current root. This step traverses the left subtree of the current node.
- Then, the code prints the value of the current root node using cout. This printing is performed as a step in the in-order traversal, where the values of the nodes are visited in ascending order.
- After printing the current node's value, the inOrder function is recursively called on the right child of the current root. This step traverses the right subtree of the current node.
