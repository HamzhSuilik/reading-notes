# Stacks and Queues

## Stacks

![image](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/stack1.PNG)

A stack is a data structure that consists of Nodes. Each Node references the next Node in the stack

Common terminology for a stack :
- Push 
- pop 
- Top 
- peak 
- IsEmpty

you would check isEmpty before pop – Top – peak functions

**FILO** (First In Last Out) : that mean that first item added in the stack will be the last item popped out of the stack

**Steps to add new item to Stack :**
- Select new free node 
- assign the next property of new Node to reference the Node that old top of Stack .
- re-assign reference Stack top to the new node

**Steps to remove top item from Stack :**
- create a reference named temp that points to the same Node that top points to
- re-assign top to the value that the next property of old top
- remove old top Node safely by clear out the next property in your current temp reference
- return the value of the temp Node that was just popped off.

When you pop something from the stack , the item that will removed is last one appended


 ## Queues

 ![image](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/Queue.PNG)

- Enqueue - Nodes or items that are added to the queue.
- Dequeue - Nodes or items that are removed from the queue. If called when the queue is empty an exception will be raised.
- Front - This is the front/first Node of the queue.
- Rear - This is the rear/last Node of the queue.
- Peek - When you peek you will view the value of the front Node in the queue. If called when the queue is empty an exception will be raised.
- IsEmpty - returns true when queue is empty otherwise returns false.

The principle of FIFO (First In First Out) is applied to Queue 

**process of adding a Node to a queue:**
- change the next property of Rear Node to point to the Node we are adding
- re-assign the rear reference to point to new Node

