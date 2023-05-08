Problem 08 : Inorder Traversal of Binary tree

- The function takes a pointer to the root node of the binary tree as its input parameter. The root node is a pointer to a Node struct, which typically contains data, left and right child pointers.
![image](https://user-images.githubusercontent.com/93985255/236871282-6262e779-82c9-41b1-aad6-28bf3f0545f7.png)


- The function first creates an empty vector res to store the inorder traversal result.

- Then it checks if the root node is not NULL. If the root node is not NULL, it recursively traverses the left subtree by calling the inOrder function on the left child of the current node. This will visit all nodes in the left subtree before the current node.

- Then the function pushes the data of the current node into the vector. This step will add the value of the current node to the vector after visiting all nodes in the left subtree.

- Next, the function recursively traverses the right subtree by calling the inOrder function on the right child of the current node. This will visit all nodes in the right subtree after the current node.

- Finally, the function returns the result vector res which contains the inorder traversal of the binary tree.
