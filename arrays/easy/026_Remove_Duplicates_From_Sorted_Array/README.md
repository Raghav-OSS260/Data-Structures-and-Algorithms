# Remove Duplicates from Sorted Array (LeetCode #26)

## Problem Statement

Given a sorted array, remove duplicates in-place such that each unique element appears only once.

Return the number of unique elements.

---

## Example

Input:

```text
nums = [1,1,2]
```

Output:

```text
2
```

Modified Array:

```text
[1,2,_]
```

---

## Pattern

Two Pointers

---

## Intuition

Since the array is sorted, duplicate elements always appear next to each other.

Use one pointer to track the position of the last unique element and another pointer to scan the array.

---

## Approach

1. Maintain two pointers.
2. Compare current element with previous unique element.
3. If different, place it at the next valid position.
4. Return count of unique elements.

---

## Complexity Analysis

Time Complexity:

```text
O(n)
```

Space Complexity:

```text
O(1)
```

---

## Key Learning

* In-place array modification.
* Two Pointer technique.
* Foundation for many array interview problems.

---

## Solution

See `solution.cpp`
