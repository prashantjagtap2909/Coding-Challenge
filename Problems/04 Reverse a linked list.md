#### Problem 04:  Reverse a linked list

  - The function takes a pointer to the head node of a singly linked list as input and returns a pointer to the head node of the reversed list.
 ![image](https://user-images.githubusercontent.com/93985255/233793953-fbf13218-d811-4bc8-9da6-a22cb3d8f4fd.png)

  - The function first checks if the input pointer is NULL, which indicates an empty list. In that case, it returns NULL since there's nothing to reverse.
  - If the input pointer is not NULL, the function initializes three pointers p, curr, and n. curr initially points to the head node of the list, while p and n are both NULL.
  - The function then enters a loop that continues until curr becomes NULL. Within this loop, it first sets the next pointer of the current node curr to p. This effectively reverses the direction of the linked list by pointing the current node to the previous node in the list.
  - Next, the function updates p and curr to the current and next nodes, respectively, using the values of n and curr->next.
  - Finally, the function checks if n is not NULL, which means there is at least one more node in the list to process. If n is not NULL, the function updates n to point to the next node in the list.
  - Once the loop ends, the function returns the pointer p, which now points to the head of the reversed list.
