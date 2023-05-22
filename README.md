# Binary Trees

This repository contains C programs that implement various operations on binary trees. A binary tree is a tree data structure in which each node has at most two children, which are referred to as the left child and the right child[^1^][1].

## Contents

This repository contains the following files:

- binary_tree.h: Header file that defines the structure of a binary tree node and some basic functions.
- 0-binary_tree_node.c: Function that creates a binary tree node.
- 1-binary_tree_insert_left.c: Function that inserts a node as the left-child of another node.
- 2-binary_tree_insert_right.c: Function that inserts a node as the right-child of another node.
- 3-binary_tree_delete.c: Function that deletes an entire binary tree.
- 4-binary_tree_is_leaf.c: Function that checks if a node is a leaf.
- 5-binary_tree_is_root.c: Function that checks if a node is a root.
- 6-binary_tree_preorder.c: Function that goes through a binary tree using pre-order traversal.
- 7-binary_tree_inorder.c: Function that goes through a binary tree using in-order traversal.
- 8-binary_tree_postorder.c: Function that goes through a binary tree using post-order traversal.
- 9-binary_tree_height.c: Function that measures the height of a binary tree.
- 10-binary_tree_depth.c: Function that measures the depth of a node in a binary tree.
- 11-binary_tree_size.c: Function that measures the size of a binary tree.
- 12-binary_tree_leaves.c: Function that counts the leaves in a binary tree.
- 13-binary_tree_nodes.c: Function that counts the nodes with at least one child in a binary tree.
- 14-binary_tree_balance.c: Function that measures the balance factor of a binary tree.
- 15-binary_tree_is_full.c: Function that checks if a binary tree is full.
- 16-binary_tree_is_perfect.c: Function that checks if a binary tree is perfect.

## Installation

To use this repository, you need to clone it to your local machine and compile the C files with gcc.

Copy
git clone https://github.com/Ghassen-bgh/binary_trees.git cd binary_trees gcc -Wall -Werror -Wextra -pedantic *.c -o binary_trees


## Usage

To run the program, you need to pass the name of a file that contains the commands to create and manipulate the binary tree. For example, you can use the file `0-main.c` to test the function `binary_tree_node`.

Copy
./binary_trees 0-main.c


The output should look like this:

Copy
(098) .-------(402) .–(012)–| (054) (128)–.-------(402) Original node: (098)

Left-child: (012)

Right-child: (128)


You can also use your own files to test other functions or create your own binary trees.

## Author

This repository was created by Ghassen Boughammoura.

## References

[1]: Binary Tree Data Structure - GeeksforGeeks https://www.geeksforgeeks.org/binary-tree-data-structure/
