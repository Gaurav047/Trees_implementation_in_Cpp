# Trees_implementation_in_Cpp
These codes were written to implement different kind of tree data structures in C++. The libraries are build to run  via a helping cpp program. In this project I have made libraries for Binary Search Tree, AVL trees and Red-Black trees. There is an implementation of dictionary too.

Required Tasks:

1. Implement the Dictionary Data-Structure.Details are given in the section below.
2. Write a pseduo-random number generator to n numbers, n taken as user input.
3. Insert the n numbers generated in task #2 into each of the BSTree, AVL and RBTree.
4. Record the number of comparisons and the depth of the trees after each insertion in a 2-3 page report. The report must contain your observations.

# Instructions for Task #1
Implement the Dictionary data structure using binary search tree (BST), AVL tree and RB Tree.
1. Create and Use a “Node” class to implement a node of a tree. (Do not use structure (struct))
2. Interfaces for the Dictionary, BST and AVL tree are given. 
Dictionary.hpp: abstract Dictionary interface.
BST.hpp: Interface for BST
AVL.hpp: Interface for AVL tree
RBTree.hpp: Interface for RB tree
3. For AVL Tree and RB Tree, inherit as much functionality as possible from the BSTree class. Then provide custom AVL (or RB) Tree functionality on top of that. The AVL (or RB) Tree should make use of as many BST functions as possible. Override only those methods which are extremely necessary.
4. Your main program should ask the user to select a BSTree or an AVL or RB Tree at run-time. Also, it should ask the user to input the key each time new key is inserted. 

Your main program should have the following menu of operations and this menu should be displayed each time after the completion of an operation:
a. Insert a key
b. Search for a key 
c. Delete a key
d. Display all the keys as observed in inorder traversal
e. Display all the keys as observed in preorder traversal
f. Display all the keys as observed in postorder traversal
g. Display all the keys as observed in levelorder traversal
h. Display the minimum key in a tree
i. Display the maximum key in a tree
j. Display the succesor of a key
k. Display the predecessor of a key
l. Display the height of a tree
m. Exit

Appropriate error-handling is expected.
