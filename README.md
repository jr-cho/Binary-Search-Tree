# Binary Search Tree (BST) Implementation in C

This repository contains a simple implementation of a Binary Search Tree (BST) in C. The program demonstrates the basic operations of a BST, such as inserting nodes, performing in-order and post-order traversals, and freeing the allocated memory for the tree.

## 🚀 Features

- **Create Node**: Function to create a new node in the tree.
- **Insert**: Function to insert a new value into the BST.
- **In-Order Traversal**: Function to print the tree nodes in ascending order.
- **Post-Order Traversal**: Function to print the tree nodes in post-order.
- **Memory Management**: Function to free all allocated memory for the tree nodes.

## ⚙️ Usage

```c
// Create a new node with data
Node* createNode(int data);

// Insert a value into the binary search tree
Node* insert(Node* root, int data);

// Perform an in-order traversal and print node values
void inorder(Node* root);

// Perform a post-order traversal and print node values
void postfix(Node* root);

// Free all allocated memory for the tree
void freeTree(Node* root);
```

## License

Distributed under the Unlicense License. See `LICENSE.txt` for more information.
