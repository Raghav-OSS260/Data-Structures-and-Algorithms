# Contains Duplicate (LeetCode #217)

## Problem Statement

Given an integer array `nums`, return `true` if any value appears at least twice in the array, and return `false` if every element is distinct.

---

## Example

### Example 1

Input:

nums = [1,2,3,1]

Output:

true

---

### Example 2

Input:

nums = [1,2,3,4]

Output:

false

---

## Pattern

Hash Set

---

## Intuition

The brute-force approach compares every pair of elements, which is inefficient.

A Hash Set allows us to quickly determine whether an element has already been seen during traversal.

---

## Approach

1. Create an empty Hash Set.
2. Traverse the array.
3. If the current element already exists in the set, return `true`.
4. Otherwise insert it into the set.
5. If traversal completes, return `false`.

---

## Complexity Analysis

### Time Complexity

O(n)

### Space Complexity

O(n)

---

## Key Learning

- Fast lookups using Hash Set.
- Duplicate detection.
- Introduction to hashing techniques.

---

## Solution

See `solution.cpp`