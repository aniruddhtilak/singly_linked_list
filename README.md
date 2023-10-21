# singly_linked_list
Basic Codes explaining concepts of linked lists
**A. Basics -** Basic code on singly-linked list
Algorithm - 
1. Create a class 'node' with data and a pointer to the next node.
2. Inside the 'node' class constructor, initialize data to 0 and next to NULL.
3. In the main function:
   a. Declare a pointer 'head' for the linked list.
   b. Create the first node, 'newnode1', set its data to 10, and assign it to 'head'.
   c. Create 'newnode2', 'newnode3', and 'newnode4' and set their data values.
   d. Link the nodes together by setting the 'next' pointers.
   e. Print the data, self-address, and next address for each node.


**B. Access data by loop -**  Updated version of previous code with a loop used for displaying the elements.
Algorithm -
1.Create a class node with data and a pointer to the next node.
2.Inside the node class constructor, initialize the data to 0 and next to NULL.
3.In the main function:
  a. Declare a pointer head for the linked list.
  b. Create the first node, newnode1, set its data to 10, and assign it to head.
  c. Create newnode2, newnode3, and newnode4, and set their data values.
  d. Link the nodes together by setting the next pointers.
  e. Print the data, self-address, and next address for each node individually.
  f. Use a while loop to traverse the linked list and print the same information for each node.


  **C.Adder function -** Uses functions to add elments at the nd of the list and display them.
  Algorithm - 
  Algorithm for Creating and Displaying a Singly Linked List:

  1. Define a class named 'node' to represent a node in a singly linked list:
   a. Declare public member variables: 'data' (to store the node's data) and 'next' (a pointer to the next node).
   b. Create a constructor to initialize 'data' to 0 and 'next' to NULL.

  2. Declare a global pointer variable 'head' to represent the head of the linked list.

  3. Create a function 'atBegining' to add a new node at the beginning of the list:
   a. Create a new node 'newnode'.
   b. Set 'data' in 'newnode' to the given 'data'.
   c. Set 'newnode->next' to the current 'head'.
   d. Update 'head' to point to 'newnode'.

  4. Create a function 'end_adder' to add a new node at the end of the list:
   a. Traverse the list from the head to the last node.
   b. Create a new node 'newnode'.
   c. Set 'data' in 'newnode' to the given 'data'.
   d. Set the 'next' of the last node to 'newnode'.

  5. Create a function 'display' to print the elements in the list:
   a. Initialize a pointer 'temp' to the 'head'.
   b. While 'temp' is not NULL, print the 'data' in the current node and move to the next node by updating 'temp' to 'temp->next'.
   c. Repeat the process until 'temp' becomes NULL.

  6. In the 'main()' function:
   a. Create several 'node' objects and set their 'data' values.
   b. Link the nodes together to form a singly linked list.
   c. Call the 'end_adder' function to add more nodes to the end.
   d. Call the 'display' function to print the linked list.

  7. End of the program.



