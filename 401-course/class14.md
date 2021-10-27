# Trees
Tree is a non-linear data structure because it does not store in a sequential manner. There are many types of trees but here we will mention only three types of trees. But first we will take a sample of tree and see how it works.


## Common Terminology
First there is a common terminology we need to discuss to know how the trees works like the node and it is the main component of the tree and may and may not contain value, root and it is the node that is in the beginning of the tree, k is the max number of children can have a single node in k-ary trees, and there is left,right,edge,leaf, and height terms that we will discuss later. 

![sample tree](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/BinaryTree1.PNG)


## Traversals

tree contains of nodes and each node contain other nodes so to get to specific node we need to traverse the tree to get to it and get the information and there are two methods to do it.

1. Depth First: it is the method we need to pass through the root to get anywhere and we have three probabilities for this method pre-order method,In-order method, and post-order method.  

2. Breadth First: it is when we have the tree going through nodes level by level root then the nodes below it then the nodes below the nodes below the root. and this one uses the queue instead of the stack.


## Binary Tree Vs K-ary Trees

### Binary trees 
when we have any type of tree, each node can have unlimited number of children however the binary only allow each node to have only two nodes either left or right. And that is not the same in the k-ary trees.

### K-ary Trees 
Unlike the binary tree k-ary tree allows a kth number of children to each node so there are no restrictions. the traversal in this type of tree looks like the traversal in the breadth first but with more nodes.

### Adding a node
When we add a node to our tree we start from the bottom of the tree or we can call it from the children to the top unless we need to get to a specific node. 

### Big O

As for the time complexity of the most of tree methods is O(n) like inserting a new node or searching for a node however the inserting using the breadth in the non-binary takes big O(w) where w is the largest width of the tree and

## Binary search trees
It is the trees who have a specific construction to them and the nodes are structured to a specific way like when we have a binary search tree. 




