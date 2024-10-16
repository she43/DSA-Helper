## Linked Lists (Basics) - Study Guide

### Introduction to Linked Lists

A **Linked List** is a linear data structure where elements are stored in nodes. Each node contains data and a reference (or link) to the next node in the sequence. Unlike arrays, linked lists do not have a fixed size and allow for dynamic memory allocation.

### Key Concepts:
1. **Node**: The building block of a linked list, containing the data and a reference to the next node.
2. **Head**: The first node in a linked list.
3. **Tail**: The last node in a linked list that points to `null`.
4. **Singly Linked List**: Each node points to the next node.
5. **Doubly Linked List**: Each node points to both the next and previous nodes.
6. **Circular Linked List**: The last node points back to the head, creating a loop.

### Types of Linked Lists:
1. **Singly Linked List**: Contains nodes with a data field and a reference to the next node.
2. **Doubly Linked List**: Nodes have references to both the next and previous nodes.
3. **Circular Linked List**: The last node is connected back to the head of the list.
4. **Circular Doubly Linked List**: A combination of a circular and doubly linked list.

---

### Common Operations:
1. **Insertion**: Adding a new node at the beginning, end, or a specific position.
2. **Deletion**: Removing a node from the list (from the beginning, end, or a specific position).
3. **Traversal**: Visiting each node in the linked list to access or process data.
4. **Search**: Finding a node with a specific value.
5. **Reversal**: Reversing the order of nodes in the linked list.
6. **Finding Middle**: Finding the middle node of the linked list in O(n) time.

---

### Time and Space Complexity:
- **Traversal/Search/Insert/Delete (Singly Linked List)**: O(n) time for worst case, O(1) space for most operations.
- **Traversal/Search (Doubly Linked List)**: O(n) time, O(1) space.
- **Insert/Delete at Head/Tail (Doubly Linked List)**: O(1) time.

---

### Applications of Linked Lists:
- **Dynamic memory allocation**: Flexible memory usage.
- **Implemented in queues and stacks**: Linked list structure is ideal for dynamic data.
- **Used in hash table chaining**: To handle collisions.
- **Music/video playlists**: With next and previous navigation.

---

### Practice Problems:

#### 1. Singly Linked List Operations
- **LeetCode**:
  - [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) (LC #206)
  - [Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/) (LC #876)
  - [Remove N-th Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) (LC #19)
  - [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/) (LC #21)
  - [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) (LC #141)
- **GeeksforGeeks**:
  - [Linked List Insertion](https://www.geeksforgeeks.org/linked-list-set-2-inserting-a-node/)
  - [Detect Loop in a Linked List](https://www.geeksforgeeks.org/detect-loop-in-a-linked-list/)
  - [Remove Duplicates from Sorted Linked List](https://www.geeksforgeeks.org/remove-duplicates-from-a-sorted-linked-list/)
  - [Find Length of a Linked List](https://www.geeksforgeeks.org/find-length-of-a-linked-list-iterative-and-recursive/)
  - [Reverse a Linked List](https://www.geeksforgeeks.org/reverse-a-linked-list/)

#### 2. Doubly Linked List
- **LeetCode**:
  - [Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/) (LC #430)
  - [Design Browser History](https://leetcode.com/problems/design-browser-history/) (LC #1472)
  - [Insert into a Sorted Doubly Linked List](https://leetcode.com/problems/insert-into-a-sorted-circular-doubly-linked-list/) (LC #708)
  - [Remove Duplicates from Sorted Doubly Linked List](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/) (LC #82)
  - [Convert Binary Search Tree to Doubly Linked List](https://leetcode.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list/) (LC #426)
- **GeeksforGeeks**:
  - [Doubly Linked List Introduction](https://www.geeksforgeeks.org/doubly-linked-list/)
  - [Insert a Node in Doubly Linked List](https://www.geeksforgeeks.org/doubly-linked-list-set-2-insertion/)
  - [Delete a Node in Doubly Linked List](https://www.geeksforgeeks.org/delete-a-node-in-a-doubly-linked-list/)
  - [Reverse a Doubly Linked List](https://www.geeksforgeeks.org/reverse-a-doubly-linked-list/)
  - [Remove Duplicates from Doubly Linked List](https://www.geeksforgeeks.org/remove-duplicates-unsorted-doubly-linked-list/)

#### 3. Circular Linked List
- **LeetCode**:
  - [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) (LC #141)
  - [Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/) (LC #142)
  - [Insert into a Sorted Circular Doubly Linked List](https://leetcode.com/problems/insert-into-a-sorted-circular-doubly-linked-list/) (LC #708)
  - [Split a Circular Linked List into Two Halves](https://leetcode.com/problems/split-linked-list-in-parts/) (LC #725)
  - [Circular Linked List Intersection](https://leetcode.com/problems/intersection-of-two-linked-lists/) (LC #160)
- **GeeksforGeeks**:
  - [Check if Circular Linked List](https://www.geeksforgeeks.org/check-if-a-linked-list-is-circular-linked-list/)
  - [Split a Circular Linked List](https://www.geeksforgeeks.org/split-a-circular-linked-list-into-two-halves/)
  - [Insert Node in Circular Linked List](https://www.geeksforgeeks.org/insert-a-node-in-a-circular-linked-list/)
  - [Sorted Insert in Circular Linked List](https://www.geeksforgeeks.org/sorted-insert-for-circular-linked-list/)
  - [Traversal of Circular Linked List](https://www.geeksforgeeks.org/circular-linked-list-traversal/)

#### 4. Advanced Linked List Problems
- **LeetCode**:
  - [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) (LC #234)
  - [Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/) (LC #160)
  - [Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) (LC #138)
  - [Sort List](https://leetcode.com/problems/sort-list/) (LC #148)
  - [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) (LC #2)
- **GeeksforGeeks**:
  - [Intersection Point in Y Shaped Linked List](https://www.geeksforgeeks.org/write-a-function-to-get-the-intersection-point-of-two-linked-lists/)
  - [Add Two Numbers Represented by Linked Lists](https://www.geeksforgeeks.org/add-two-numbers-represented-by-linked-lists/)
  - [Merge Sort for Linked List](https://www.geeksforgeeks.org/merge-sort-for-linked-list/)
  - [Clone a Linked List with Random Pointers](https://www.geeksforgeeks.org/a-linked-list-with-next-and-arbit-pointer/)
  - [Check if Linked List is a Palindrome](https://www.geeksforgeeks.org/function-to-check-if-a-singly-linked-list-is-palindrome/)
