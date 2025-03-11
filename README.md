# Binary Search Tree (BST) Implementation in C

This repository contains a simple implementation of a Binary Search Tree (BST) in C. The program demonstrates the basic operations of a BST, such as inserting nodes, performing in-order and post-order traversals, and freeing the allocated memory for the tree.

## Features

- **Create Node**: Function to create a new node in the tree.
- **Insert**: Function to insert a new value into the BST.
- **In-Order Traversal**: Function to print the tree nodes in ascending order.
- **Post-Order Traversal**: Function to print the tree nodes in post-order.
- **Memory Management**: Function to free all allocated memory for the tree nodes.

## Functions

### `Node* createNode(int data)`
Creates a new node with the given `data` and returns a pointer to it. The node's left and right child pointers are initialized to `NULL`.

### `Node* insert(Node* root, int data)`
Inserts a new node with the given `data` into the tree. The function recursively finds the correct position for the new node based on the binary search tree properties.

### `void inorder(Node* root)`
Performs an in-order traversal of the binary search tree and prints the node values. The traversal visits nodes in ascending order.

### `void postfix(Node* root)`
Performs a post-order traversal of the binary search tree and prints the node values. The traversal visits the left and right subtrees before the current node.

### `void freeTree(Node* root)`
Recursively frees the memory allocated for the tree nodes to prevent memory leaks.
