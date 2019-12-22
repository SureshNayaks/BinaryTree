# BinaryTree
Binary Search Tree:
A binary search tree is a data structure that allows for key lookup, insertion, and deletion. It is a
binary tree, meaning every node x of the tree has at most two child nodes, a left child and a right
child. Each node of the tree holds the following information:


• x.key - Value stored in node x.
• x.left- Pointer to the left child of node x. NIL if x has no left child.
• x.right - Pointer to the right child of node x. NIL if x has no right child.
• x.parent - Pointer to the parent node of node x. NIL if x has no parent, i.e. x is the root of
the tree.






Binary search tree has the following invariants:
• For each node x, every key found in the left subtree of x is less than or equal to the key found
in x.
• For each node x, every key found in the right subtree of x is greater than or equal to the key
found in x.



BST Operations:
There are operations of a binary search tree that take advantage of the properties above to search
for keys. There are other operations that manipulate the tree to insert new keys or remove old ones
while maintaining these two invariants.
In the lecture, we saw find(k), insert(x), find min() and find max(). They
all have O(h) running time where h is the height of the tree. Today, we will look at two more
operations.



