# Linked Lists

A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.
There are two types of Linked List :
- Singly 
- Doubly


Singly - Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
Doubly - Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.
Node - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
Next - Each node contains a property called Next. This property contains the reference to the next node.
Head - The Head is a reference of type Node to the first node in a linked list.
Current - The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list.

The Next lead us where the next node is and allow us to extract the data appropriately.

To looping inside Linked list use while statement and use next to move to the next node after every iteration until  reach to null value (last node)

Head is always the first node in a Linked List so to ensure that we starting from the beginning Linked list , we should creating Current at the Head

**steps to add a new node with an O(1) :**
- Using Add() method to define the value of the new Node .
- Use newNode.Next  to set newNode.Next property to the same location that the Head node is pointing towards
- to re-assign where Head is pointing , to point at newNode


