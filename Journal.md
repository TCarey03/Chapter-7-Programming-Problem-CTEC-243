Phase 1: Foundation (Nodes and Insertion)

I created the BSTNode class to store each value and references to its left and right children. I also created the BinarySearchTree class to manage the nodes and insert new accession IDs.

The add method compares each new value with the current node. If the value is less than or equal to the current value, it goes left. If it is greater, it goes right. This continues until an empty spot is found.

The Comparable interface is required because it allows Java to compare values and determine where they belong in the tree. I tested the program using the sample IDs and confirmed that the archive initialized successfully.
