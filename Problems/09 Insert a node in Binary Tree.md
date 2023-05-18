Problem 09: Insert a node in Binary Tree

- This is the insertion of a node into a binary search tree

- The insert() function takes two parameters: root, which represents the root node of the BST, and key, which is the value to be inserted into the BST.
![image](https://github.com/prashantjagtap2909/Coding-Challenge/assets/93985255/8e2bcf37-8ff2-41ea-b903-e4d5c5ca2914)

- Initially, the function checks if the root is NULL, which indicates an empty tree. If it is NULL, a new node temp is created with the given key value, and it becomes the root of the BST. The function then returns the temp node.
- If the root is not NULL, the function proceeds to check if the key value is already present in the BST. If it is, the function simply returns the root without making any changes to the tree.
- If the key value is not present in the BST, the function determines the correct position to insert the new node based on the property of a BST. If the key is greater than the root->data, it means the new node should be inserted in the right subtree.
- The insert() function is recursively called with the root->right as the new root and the key value. The return value of this recursive call is assigned to root->right, connecting the new node to the right subtree.
- If the key value is less than the root->data, it means the new node should be inserted in the left subtree. The insert() function is recursively called with the root->left as the new root and the key value.
- The return value of this recursive call is assigned to root->left, connecting the new node to the left subtree.

- Finally, the function returns the root node, which represents the modified BST after the insertion.
