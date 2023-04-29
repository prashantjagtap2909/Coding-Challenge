#### Problem 7: To check element is present of not in the Binary search tree.

- This is a code to find a given integer value x in a BST. The function takes two arguments: a pointer to the root of the BST, and the value x that needs to be searched.
![image](https://user-images.githubusercontent.com/93985255/235307984-7ee80784-f999-434b-bda0-937f8814bfc3.png)
- The function starts by checking if the root node is not NULL, which means that the BST is not empty. If the root node's data matches the value x, then the function immediately returns true, as the value has been found in the BST.
- If the root node's data is less than x, then the value x can only be present in the right subtree of the root node. 
So, the function updates the root pointer to point to the right subtree and continues searching from there.
- If the root node's data is greater than x, then the value x can only be present in the left subtree of the root node.
 So, the function updates the root pointer to point to the left subtree and continues searching from there. 
- The search continues in this way until either the value x is found in the BST, in which case the function returns true, or the root node becomes NULL, indicating that the value x is not present in the BST. In this case, the function returns false.
 
