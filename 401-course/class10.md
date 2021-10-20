# Stacks & Queues


## Stacks

As the linked lists stacks are a data structure that consists of nodes and each node points or reference to the next node in the pile of nodes. also it does not point to the previous node.

stacks follows these patterns whenever we need to push or do any other things:

* FILO or first in first out.
* LIFO or last in first out.

![stacks](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/stack1.PNG)

There are different changes or moves you can do by the nodes inside the stacks such as:

1. Push O(1): it is when we want to add new node to the stack and the last one you push, will be at the top.
2. pop(1): it is when we want to pull node from the stack.
3. Peek O(1): It is used to show top node.
4. isEmpty: It is to show when the stack is empty.


## Queue
It is when a group of nodes is waiting to get processed in the line and it follows these concepts:

* FIFO: first node in first node out.
* LILO: last node in last node out.

![visualization for the queue](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/Queue.PNG)

### Enqueue O(1) 
It is the process of adding an item to the queue and it is an big O(1). the process is done using LILO.

### Dequeue O(1)
It is the process of removing a node from the queue and the one who will be always removed is the front item so it follows FIFO.

### Peek O(1)

It is used to show the front node, and it is needed to check if it is empty always so we isEmpty.

### IsEmpty O(1)
Used to check code if it is empty or not.