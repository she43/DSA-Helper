## Trees (Basics) - Study Guide

### Introduction to Trees

A **tree** is a widely used abstract data type (ADT) that simulates a hierarchical tree structure, with a root value and subtrees of children with a parent node, represented as a set of linked nodes.

---

### Key Concepts:
1. **Node**: A node contains data and may have links to other nodes.
2. **Root**: The topmost node in a tree, without a parent.
3. **Edge**: A connection between two nodes.
4. **Child**: A node directly connected to another node when moving away from the root.
5. **Parent**: The converse notion of a child.
6. **Leaf**: A node that has no children.
7. **Subtree**: A tree formed from a node and its descendants.
8. **Height**: The number of edges on the longest path from a node to a leaf.
9. **Depth**: The number of edges from the root to the node.
10. **Binary Tree**: A tree in which each node has at most two children.

---

### Common Types of Trees:

- **Binary Tree**: A tree where each node has at most two children.
- **Binary Search Tree (BST)**: A binary tree where the left subtree of a node contains only nodes with values lesser than the node, and the right subtree only nodes with values greater than the node.
- **Balanced Tree**: A tree where the height difference between subtrees of every node is minimal, ensuring logarithmic time operations.

---

### Tree Traversal Methods:

1. **Pre-order Traversal (Root, Left, Right)**: Visit the root node first, followed by the left subtree and then the right subtree.
2. **In-order Traversal (Left, Root, Right)**: Visit the left subtree first, followed by the root, then the right subtree.
3. **Post-order Traversal (Left, Right, Root)**: Visit the left subtree, the right subtree, and then the root node.
4. **Level-order Traversal (Breadth-first Search)**: Visit nodes level by level, starting from the root.

---

### Operations on Trees:
- **Insertion**: Adding a node to the tree in a way that maintains its structure.
- **Deletion**: Removing a node, which may require restructuring.
- **Search**: Finding a node with a given value.

---

### Common Algorithms:

1. **Tree Traversal Algorithms**: DFS (Pre-order, In-order, Post-order), BFS (Level-order).
2. **Height Calculation**: Recursively compute the height of a tree.
3. **Lowest Common Ancestor (LCA)**: Finding the lowest common ancestor of two nodes.
4. **Checking Balanced Trees**: Determine if a tree is height-balanced.

---

### Time and Space Complexity:

- **Traversal**: O(n) time, O(h) space (h = height of tree)
- **Insertion/Search (BST)**: O(h) time (O(log n) for balanced trees)
- **Deletion (BST)**: O(h) time

---

### Applications of Trees:

- **Binary Search Trees**: Efficient searching, insertion, and deletion operations.
- **Heaps**: Used in priority queues.
- **Tries**: Efficient for string searching.
- **Segment Trees**: Efficient range queries.

---

### Practice Problems:

#### 1. Tree Traversal (Pre-order, In-order, Post-order, Level-order)
- **LeetCode**:
  - [Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/) (LC #144)
  - [Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) (LC #94)
  - [Binary Tree Postorder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/) (LC #145)
  - [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) (LC #102)
  - [Binary Tree Zigzag Level Order Traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) (LC #103)
- **GeeksforGeeks**:
  - [Level Order Traversal](https://www.geeksforgeeks.org/level-order-tree-traversal/)
  - [Inorder Tree Traversal without Recursion](https://www.geeksforgeeks.org/inorder-tree-traversal-without-recursion/)

#### 2. Binary Search Tree (BST)
- **LeetCode**:
  - [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/) (LC #98)
  - [Insert into a Binary Search Tree](https://leetcode.com/problems/insert-into-a-binary-search-tree/) (LC #701)
  - [Delete Node in a BST](https://leetcode.com/problems/delete-node-in-a-bst/) (LC #450)
  - [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) (LC #230)
  - [Lowest Common Ancestor of a Binary Search Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) (LC #235)
- **GeeksforGeeks**:
  - [Check if a Binary Tree is BST](https://www.geeksforgeeks.org/a-program-to-check-if-a-binary-tree-is-bst-or-not/)
  - [Find K-th Smallest Element in BST](https://www.geeksforgeeks.org/kth-smallest-element-in-bst-using-o1-extra-space/)

#### 3. Balanced Trees (AVL/Height-Balanced)
- **LeetCode**:
  - [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/) (LC #110)
  - [Minimum Height Trees](https://leetcode.com/problems/minimum-height-trees/) (LC #310)
  - [Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) (LC #108)
  - [Check Completeness of a Binary Tree](https://leetcode.com/problems/check-completeness-of-a-binary-tree/) (LC #958)
  - [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) (LC #124)
- **GeeksforGeeks**:
  - [Check if a Binary Tree is Height Balanced](https://www.geeksforgeeks.org/how-to-determine-if-a-binary-tree-is-balanced/)
  - [Check if all Levels of Two Trees are Anagrams or Not](https://www.geeksforgeeks.org/check-if-all-levels-of-two-trees-are-anagrams-or-not/)

#### 4. Lowest Common Ancestor (LCA)
- **LeetCode**:
  - [Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) (LC #236)
  - [Lowest Common Ancestor of a Binary Search Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) (LC #235)
  - [Binary Tree LCA III](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree-iii/) (LC #1650)
  - [Lowest Common Ancestor of Deepest Leaves](https://leetcode.com/problems/lowest-common-ancestor-of-deepest-leaves/) (LC #1123)
  - [Smallest Common Region](https://leetcode.com/problems/smallest-common-region/) (LC #1257)
- **GeeksforGeeks**:
  - [Lowest Common Ancestor in Binary Tree](https://www.geeksforgeeks.org/lowest-common-ancestor-binary-tree-set-1/)
  - [Find LCA in a Binary Search Tree](https://www.geeksforgeeks.org/lowest-common-ancestor-in-a-binary-search-tree/)

#### 5. Tree Height & Depth
- **LeetCode**:
  - [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) (LC #104)
  - [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) (LC #543)
  - [Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/) (LC #111)
  - [Sum of Left Leaves](https://leetcode.com/problems/sum-of-left-leaves/) (LC #404)
  - [Path Sum](https://leetcode.com/problems/path-sum/) (LC #112)
- **GeeksforGeeks**:
  - [Find the Height of a Binary Tree](https://www.geeksforgeeks.org/write-a-c-program-to-find-the-maximum-depth-or-height-of-a-tree/)
  - [Diameter of Binary Tree](https://www.geeksforgeeks.org/diameter-of-a-binary-tree-in-on-a-new-method/)
