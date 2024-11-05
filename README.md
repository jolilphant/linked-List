Objective:
In this assignment, you’ll extend your knowledge of linked lists by converting your existing singly linked list to a doubly linked list. Additionally, you’ll add a sort method to organize the list in ascending order. This project will help you understand bidirectional node linking and sorting algorithms within a data structure.

Instructions:
Class Setup:

Modify the Node class to support a doubly linked list structure by adding a prev pointer.
Update the Linked_list class to support bidirectional node traversal.
Your doubly linked list should still contain a head node and should now also include a tail node.
Modifying the Methods: In your Linked_list class, make the following updates:

Node Class:

Add a prev pointer to each node to link to the previous node in the list.
insert(data, position):

Update this method to correctly link nodes in both directions.
Ensure that if the node is inserted at the head or tail, the pointers are adjusted accordingly.
delete(data):

Update this method so that nodes are removed without breaking the bidirectional links.
Adjust prev and next pointers for the surrounding nodes.
append(data):

Modify this method to add nodes at the end while maintaining both next and prev pointers.
print():

Update print() to print the list in both forward and reverse order. This will help confirm that the doubly linked structure is working correctly.
min() and max():

No changes are required here, but verify that these methods work correctly with the doubly linked list structure.
New Method: sort()

Add a sort() method to arrange the list in ascending order.
Use any sorting algorithm (e.g., insertion sort, bubble sort) that works well with linked lists.
Ensure that the sort() method maintains both prev and next links correctly throughout the sorting process.
After sorting, confirm that the list is in ascending order by using the print() method to display the sorted list.
Example Usage: After implementing the methods, create a linked list, test all methods, and sort the list. Demonstrate each method to ensure functionality.
