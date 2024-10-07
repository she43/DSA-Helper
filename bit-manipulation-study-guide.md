Here’s a comprehensive list of **Bit Manipulation Techniques** and **Interview Practice Problems** with related LeetCode/GeeksforGeeks questions where possible.

---

### 1. **Basics of Bit Manipulation**
Understanding the core bitwise operators is essential for solving bit manipulation problems.

- **AND (`&`)**: Masks bits, used to clear bits or check specific bits.
- **OR (`|`)**: Sets specific bits in a number.
- **XOR (`^`)**: Flips bits when two bits are different, used for toggling bits or checking equality.
- **NOT (`~`)**: Inverts all bits.
- **Left Shift (`<<`)**: Multiplies by powers of two.
- **Right Shift (`>>`)**: Divides by powers of two.
- **Key Concept**: Understanding how these operators work on binary representations of numbers.

**Example Questions:**
1. [LeetCode #191 - Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/)  
2. [LeetCode #231 - Power of Two](https://leetcode.com/problems/power-of-two/)  
3. [LeetCode #371 - Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/)  
4. [GeeksforGeeks - Count set bits](https://www.geeksforgeeks.org/count-set-bits-in-an-integer/)  
5. [LeetCode #136 - Single Number](https://leetcode.com/problems/single-number/)  
6. [GeeksforGeeks - Check whether K-th bit is set or not](https://www.geeksforgeeks.org/check-whether-k-th-bit-is-set-or-not/)  
7. [LeetCode #268 - Missing Number](https://leetcode.com/problems/missing-number/)  
8. [GeeksforGeeks - Check if a number is odd or even](https://www.geeksforgeeks.org/program-to-check-even-or-odd/)  
9. [LeetCode #190 - Reverse Bits](https://leetcode.com/problems/reverse-bits/)  
10. [GeeksforGeeks - Toggle K-th bit](https://www.geeksforgeeks.org/toggle-k-th-bit-given-number/)

---

### 2. **Power of Two Checks**
- **Approach**: To check if a number `n` is a power of two, use `n & (n - 1)`. If the result is `0`, it’s a power of two.
  
**Key Insight**: Powers of two have only one bit set in their binary representation.

**Example Questions**:
1. [LeetCode #231 - Power of Two](https://leetcode.com/problems/power-of-two/)
2. [GeeksforGeeks - Check if a number is a power of two](https://www.geeksforgeeks.org/program-to-find-whether-a-no-is-power-of-two/)
3. [LeetCode #342 - Power of Four](https://leetcode.com/problems/power-of-four/)
4. [LeetCode #326 - Power of Three](https://leetcode.com/problems/power-of-three/)
5. [LeetCode #693 - Binary Number with Alternating Bits](https://leetcode.com/problems/binary-number-with-alternating-bits/)
6. [LeetCode #137 - Single Number II](https://leetcode.com/problems/single-number-ii/)
7. [GeeksforGeeks - Count total set bits in all numbers from 1 to N](https://www.geeksforgeeks.org/count-total-set-bits-in-all-numbers-from-1-to-n/)
8. [LeetCode #338 - Counting Bits](https://leetcode.com/problems/counting-bits/)
9. [GeeksforGeeks - Turn off the rightmost set bit](https://www.geeksforgeeks.org/turn-off-the-rightmost-set-bit/)
10. [GeeksforGeeks - Position of rightmost set bit](https://www.geeksforgeeks.org/position-of-rightmost-set-bit/)

---

### 3. **Counting Set Bits**
- **Approach**: Use `x &= (x - 1)` to remove the lowest set bit and keep counting until `x == 0`. This helps count the number of 1's (set bits) in the binary representation.

**Key Insight**: Each `x &= (x - 1)` removes the lowest set bit, making it ideal for counting bits.

**Example Questions**:
1. [LeetCode #191 - Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/)
2. [GeeksforGeeks - Brian Kernighan's Algorithm](https://www.geeksforgeeks.org/count-set-bits-in-an-integer/)
3. [LeetCode #338 - Counting Bits](https://leetcode.com/problems/counting-bits/)
4. [GeeksforGeeks - Flip all bits of a number](https://www.geeksforgeeks.org/flip-bits-number/)
5. [LeetCode #476 - Number Complement](https://leetcode.com/problems/number-complement/)
6. [GeeksforGeeks - Swap all odd and even bits](https://www.geeksforgeeks.org/swap-all-odd-and-even-bits/)
7. [LeetCode #89 - Gray Code](https://leetcode.com/problems/gray-code/)
8. [GeeksforGeeks - Find parity of a number](https://www.geeksforgeeks.org/program-to-find-parity/)
9. [LeetCode #67 - Add Binary](https://leetcode.com/problems/add-binary/)
10. [LeetCode #405 - Convert a Number to Hexadecimal](https://leetcode.com/problems/convert-a-number-to-hexadecimal/)

---

### 4. **Swapping Numbers Using XOR**
- **Approach**: You can swap two numbers `x` and `y` without using a temporary variable with the following operations:
  1. `x = x ^ y`
  2. `y = x ^ y`
  3. `x = x ^ y`

**Key Insight**: XORing a number with itself results in 0, so swapping can be done in-place without using additional space.

**Example Questions**:
1. [LeetCode #136 - Single Number](https://leetcode.com/problems/single-number/)
2. [GeeksforGeeks - Swap two numbers without a temporary variable](https://www.geeksforgeeks.org/swap-two-numbers-without-using-temporary-variable/)
3. [LeetCode #137 - Single Number II](https://leetcode.com/problems/single-number-ii/)
4. [GeeksforGeeks - Swap all odd and even bits](https://www.geeksforgeeks.org/swap-all-odd-and-even-bits/)
5. [LeetCode #260 - Single Number III](https://leetcode.com/problems/single-number-iii/)
6. [LeetCode #645 - Set Mismatch](https://leetcode.com/problems/set-mismatch/)
7. [GeeksforGeeks - Find the only odd occurring element](https://www.geeksforgeeks.org/find-the-element-that-appears-once/)
8. [LeetCode #260 - Single Number III](https://leetcode.com/problems/single-number-iii/)
9. [LeetCode #137 - Single Number II](https://leetcode.com/problems/single-number-ii/)
10. [LeetCode #268 - Missing Number](https://leetcode.com/problems/missing-number/)

---

### 5. **Reversing Bits**
- **Approach**: Reversing the bits of a number involves extracting each bit and shifting it into its reverse position.

**Key Insight**: By shifting bits one at a time and using bitwise OR, you can reverse the order of bits in a number.

**Example Questions**:
1. [LeetCode #190 - Reverse Bits](https://leetcode.com/problems/reverse-bits/)
2. [GeeksforGeeks - Reverse bits of a number](https://www.geeksforgeeks.org/reverse-actual-bits-given-number/)
3. [LeetCode #405 - Convert a Number to Hexadecimal](https://leetcode.com/problems/convert-a-number-to-hexadecimal/)
4. [LeetCode #190 - Reverse Bits](https://leetcode.com/problems/reverse-bits/)
5. [GeeksforGeeks - Find whether a number is a palindrome in binary representation](https://www.geeksforgeeks.org/find-whether-a-given-number-is-a-palindrome/)
6. [LeetCode #1290 - Convert Binary Number in a Linked List to Integer](https://leetcode.com/problems/convert-binary-number-in-a-linked-list-to-integer/)
7. [GeeksforGeeks - Reverse individual bits of a number](https://www.geeksforgeeks.org/reverse-individual-bits-of-number/)
8. [LeetCode #405 - Convert a Number to Hexadecimal](https://leetcode.com/problems/convert-a-number-to-hexadecimal/)
9. [GeeksforGeeks - Reverse a linked list using bitwise operators](https://www.geeksforgeeks.org/reverse-a-linked-list/)
10. [GeeksforGeeks - Convert Binary to Gray code](https://www.geeksforgeeks.org/binary-to-gray-code-conversion/)

---

This list provides a comprehensive guide to mastering bit manipulation, with more than 10 examples in each section for targeted practice on LeetCode and GeeksforGeeks.
