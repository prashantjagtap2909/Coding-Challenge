
#### Problem 6: Merge two sorted LL.

- This is the code of merge function for merging two sorted linked lists, head1 and head2, into a single sorted linked list. The function takes the heads of the two lists as input and returns the head of the merged list.
![image](https://user-images.githubusercontent.com/93985255/234627896-4e51c9b1-3fcf-4346-b735-795445d0965b.png)

- The basic idea behind the merge function is to compare the nodes at the head of each list and append the smaller node to the merged list. 
We first check if either of the lists is empty, and if so, return the other list as the merged list.
- We create a new linked list head and tail pointer to keep track of the merged list. 
We then compare the first node of both lists and append the smaller node to the merged list. 
We update the head and tail pointers accordingly.
- We continue comparing the nodes at the heads of each list and append the smaller node to the merged list until we traversed through both the lists. Finally, we append the remaining nodes of either list to the merged list by simply pointing the tail pointer to the remaining list
- Once we have merged the two lists, we return the head of the merged list.

