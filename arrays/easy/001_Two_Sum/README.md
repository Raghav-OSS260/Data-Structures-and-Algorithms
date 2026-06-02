# Two Sum (LeetCode #1)

## Problem Statement

Given an array of integers `nums` and an integer `target`, return the indices of the two numbers such that they add up to the target.

You may assume that each input has exactly one solution, and you may not use the same element twice.

---

## Example

### Example 1

Input:

```text
nums = [2,7,11,15]
target = 9
```

Output:

```text
[0,1]
```

Explanation:

```text
nums[0] + nums[1] = 2 + 7 = 9
```

---

## Pattern

Hash Map

---

## Intuition

For every element, check whether the complement `(target - current_element)` has already been seen.

If yes, we have found our answer.

If no, store the current element and its index in a hash map.

---

## Approach

1. Create a hash map.
2. Traverse the array.
3. Calculate complement = target - nums[i].
4. If complement exists in the hash map, return the indices.
5. Otherwise store the current number and index.

---

## Complexity Analysis

### Time Complexity

```text
O(n)
```

### Space Complexity

```text
O(n)
```

---

## Key Learning

* Introduction to Hash Maps.
* Trade extra space for faster lookup.
* One of the most important interview patterns.

---

## Solution

See `solution.cpp`
