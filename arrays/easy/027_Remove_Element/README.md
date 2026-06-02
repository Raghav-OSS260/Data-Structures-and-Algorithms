# Remove Element (LeetCode #27)

## Problem Statement

Given an integer array `nums` and an integer `val`, remove all occurrences of `val` in-place. The relative order of the elements may be changed.

Return the number of elements in `nums` that are not equal to `val`.

---

## Example

### Example 1

Input:

nums = [3,2,2,3]
val = 3

Output:

2

Modified Array:

[2,2]

---

## Pattern

Two Pointers

---

## Intuition

We need to remove a specific value from the array without using extra space. Instead of creating a new array, we can overwrite unwanted elements while traversing the array.

The Two Pointer technique helps us keep track of where the next valid element should be placed.

---

## Approach

1. Initialize a pointer `k = 0`.
2. Traverse the array.
3. If the current element is not equal to `val`, place it at index `k`.
4. Increment `k`.
5. After traversal, `k` represents the number of valid elements.

---

## Complexity Analysis

### Time Complexity

O(n)

### Space Complexity

O(1)

---

## Key Learning

- In-place array modification.
- Two Pointer technique.
- Efficient removal of elements without extra memory.

---

## Solution

See `solution.cpp`