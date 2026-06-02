# Missing Number (LeetCode #268)

## Problem Statement

Given an array containing `n` distinct numbers taken from the range `[0, n]`, return the only number in the range that is missing from the array.

---

## Example

### Example 1

Input:

nums = [3,0,1]

Output:

2

---

### Example 2

Input:

nums = [0,1]

Output:

2

---

## Pattern

Mathematics / XOR

---

## Intuition

The numbers are supposed to contain every value from `0` to `n`.

If we know the expected sum of numbers from `0` to `n`, we can subtract the actual sum of the array to find the missing value.

---

## Approach

### Mathematical Approach

1. Calculate the expected sum using:

   Sum = n × (n + 1) / 2

2. Calculate the actual sum of the array.
3. Return the difference.

---

## Complexity Analysis

### Time Complexity

O(n)

### Space Complexity

O(1)

---

## Alternative Approach

Use XOR operation.

Properties:

- a ⊕ a = 0
- a ⊕ 0 = a

XOR all numbers from `0` to `n` and all array elements. The remaining value will be the missing number.

---

## Key Learning

- Mathematical optimization.
- XOR properties.
- Solving problems without extra memory.

---

## Solution

See `solution.cpp`