## Arrays (Basics) - Study Guide

### Introduction to Arrays

An **array** is a data structure consisting of a collection of elements, each identified by an array index or key. Arrays are used to store multiple items of the same type together, making them one of the most fundamental data structures in computer science.

### Key Concepts:
1. **Elements**: Individual items in the array.
2. **Index**: The position of an element in the array. Indexing typically starts from 0.
3. **Size**: The number of elements in the array.
4. **Fixed Size**: In most languages (like C, Java), arrays have a fixed size, while in Python, lists can grow dynamically.

---

### Common Operations on Arrays:
1. **Traversal**: Accessing each element of the array in sequence.
2. **Insertion**: Adding a new element to the array.
3. **Deletion**: Removing an element from the array.
4. **Search**: Finding an element in the array.
5. **Updating**: Modifying the value of an element at a specific index.

---

### Time and Space Complexity:

- **Traversal/Update**: O(n) time for traversal, O(1) time for accessing or updating a specific element.
- **Insertion/Deletion**: O(n) time (if done in the middle or beginning).
- **Search**: O(n) time for linear search.

---

### Applications of Arrays:
- **Storing data**: Efficiently stores items of the same type.
- **Used in matrix operations**: Representing multi-dimensional arrays.
- **Used in dynamic programming**: Storing solutions to sub-problems.
- **Efficient random access**: Direct access to elements using indices.

---

### Practice Problems:

#### 1. Array Traversal and Basic Operations
- **LeetCode**:
  - [Find Numbers with Even Number of Digits](https://leetcode.com/problems/find-numbers-with-even-number-of-digits/) (LC #1295)
  - [Max Consecutive Ones](https://leetcode.com/problems/max-consecutive-ones/) (LC #485)
  - [Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) (LC #977)
  - [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) (LC #26)
  - [Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) (LC #724)
- **GeeksforGeeks**:
  - [Find the Largest Element in an Array](https://www.geeksforgeeks.org/c-program-find-largest-element-array/)
  - [Array Rotation](https://www.geeksforgeeks.org/array-rotation/)
  - [Find the Sum of Array Elements](https://www.geeksforgeeks.org/c-program-find-sum-array-elements/)
  - [Reverse an Array](https://www.geeksforgeeks.org/write-a-program-to-reverse-an-array-or-string/)
  - [Check if a Key Exists in an Array](https://www.geeksforgeeks.org/check-key-present-array-java/)

#### 2. Insertion and Deletion in Arrays
- **LeetCode**:
  - [Remove Element](https://leetcode.com/problems/remove-element/) (LC #27)
  - [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) (LC #88)
  - [Insert into Sorted Array](https://leetcode.com/problems/search-insert-position/) (LC #35)
  - [Remove Duplicates from Sorted Array II](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/) (LC #80)
  - [Move Zeroes](https://leetcode.com/problems/move-zeroes/) (LC #283)
- **GeeksforGeeks**:
  - [Insert an Element at a Specific Position](https://www.geeksforgeeks.org/insert-an-element-at-a-specific-position-in-an-array/)
  - [Delete an Element from an Array](https://www.geeksforgeeks.org/c-program-to-delete-an-element-in-an-array/)
  - [Move All Zeroes to the End of an Array](https://www.geeksforgeeks.org/move-zeroes-end-array/)
  - [Merge Two Sorted Arrays](https://www.geeksforgeeks.org/merge-two-sorted-arrays/)
  - [Remove Duplicates from an Unsorted Array](https://www.geeksforgeeks.org/remove-duplicates-from-an-unsorted-array/)

#### 3. Searching in Arrays
- **LeetCode**:
  - [Binary Search](https://leetcode.com/problems/binary-search/) (LC #704)
  - [Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) (LC #34)
  - [Search Insert Position](https://leetcode.com/problems/search-insert-position/) (LC #35)
  - [Peak Index in a Mountain Array](https://leetcode.com/problems/peak-index-in-a-mountain-array/) (LC #852)
  - [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) (LC #153)
- **GeeksforGeeks**:
  - [Linear Search](https://www.geeksforgeeks.org/linear-search/)
  - [Binary Search](https://www.geeksforgeeks.org/binary-search/)
  - [Find the Missing Number](https://www.geeksforgeeks.org/find-the-missing-number/)
  - [Find the First and Last Occurrence of an Element](https://www.geeksforgeeks.org/find-first-and-last-positions-of-an-element-in-a-sorted-array/)
  - [Find the Peak Element](https://www.geeksforgeeks.org/find-peak-element/)

#### 4. Array Sorting
- **LeetCode**:
  - [Sort Colors](https://leetcode.com/problems/sort-colors/) (LC #75)
  - [Merge Intervals](https://leetcode.com/problems/merge-intervals/) (LC #56)
  - [Third Maximum Number](https://leetcode.com/problems/third-maximum-number/) (LC #414)
  - [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) (LC #448)
  - [Sort Array By Parity](https://leetcode.com/problems/sort-array-by-parity/) (LC #905)
- **GeeksforGeeks**:
  - [Bubble Sort](https://www.geeksforgeeks.org/bubble-sort/)
  - [Selection Sort](https://www.geeksforgeeks.org/selection-sort/)
  - [Insertion Sort](https://www.geeksforgeeks.org/insertion-sort/)
  - [QuickSort](https://www.geeksforgeeks.org/quick-sort/)
  - [Merge Sort](https://www.geeksforgeeks.org/merge-sort/)

#### 5. Two-Pointer Techniques
- **LeetCode**:
  - [Two Sum](https://leetcode.com/problems/two-sum/) (LC #1)
  - [Container With Most Water](https://leetcode.com/problems/container-with-most-water/) (LC #11)
  - [3Sum](https://leetcode.com/problems/3sum/) (LC #15)
  - [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) (LC #26)
  - [Move Zeroes](https://leetcode.com/problems/move-zeroes/) (LC #283)
- **GeeksforGeeks**:
  - [Two Sum Problem](https://www.geeksforgeeks.org/two-pointers-technique/)
  - [Three Sum Problem](https://www.geeksforgeeks.org/find-a-triplet-that-sum-to-a-given-value/)
  - [Move Negative Numbers to Beginning](https://www.geeksforgeeks.org/move-negative-numbers-beginning-positive-end-constant-extra-space/)
  - [Find Pair with Given Sum](https://www.geeksforgeeks.org/find-a-pair-with-the-given-difference/)
  - [Find Triplet with Zero Sum](https://www.geeksforgeeks.org/find-triplets-array-whose-sum-equal-zero/)
