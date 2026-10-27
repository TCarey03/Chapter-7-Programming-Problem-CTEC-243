Phase 1: Foundation (Nodes and Insertion)

I created the BSTNode class to store each value and references to its left and right children. I also created the BinarySearchTree class to manage the nodes and insert new accession IDs.

The add method compares each new value with the current node. If the value is less than or equal to the current value, it goes left. If it is greater, it goes right. This continues until an empty spot is found.

The Comparable interface is required because it allows Java to compare values and determine where they belong in the tree. I tested the program using the sample IDs and confirmed that the archive initialized successfully.

--------------------

Phase 2: Archive Depth (Tree Height)

In this phase, I added a height method to calculate the maximum depth of the binary search tree. The method uses recursion to check the heights of the left and right subtrees. When it reaches a null node, it returns -1. It then uses Math.max() to find the taller subtree and adds 1 to calculate the current height.

I tested the program with the sample accession IDs and got a height of 2. This makes sense because the root is at Level 0 and the deepest nodes are at Level 2.

--------------------

Phase 3: Catalog Audits (Traversals)

In this phase, I added inorder and preorder traversal methods to my binary search tree. The inorder traversal visits the left subtree, prints the current node, and then visits the right subtree. It prints the accession IDs in ascending order because smaller values are stored on the left and larger values are stored on the right.

The preorder traversal prints the current node first, followed by the left and right subtrees. I tested both methods using the sample IDs and confirmed that the output matched the expected results.
