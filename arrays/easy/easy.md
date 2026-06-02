# Easy Array Problems

This document contains classic Easy Array problems frequently asked in coding interviews and online assessments. Each problem includes a brief overview, sample test case, and the primary pattern used to solve it.

---

## 1. Two Sum

**Overview:** Find two indices whose elements add up to a target value.

**Example:**
Input: nums = [2,7,11,15], target = 9

Output:
[0,1]

**Pattern:** Hash Map

---

## 2. Remove Duplicates from Sorted Array

**Overview:** Remove duplicates in-place from a sorted array.

**Example:**
Input: [1,1,2]

Output:
[1,2]

**Pattern:** Two Pointers

---

## 3. Remove Element

**Overview:** Remove all occurrences of a given value.

**Example:**
Input: nums = [3,2,2,3], val = 3

Output:
[2,2]

**Pattern:** Two Pointers

---

## 4. Contains Duplicate

**Overview:** Determine whether any value appears at least twice.

**Example:**
Input: [1,2,3,1]

Output:
true

**Pattern:** Hash Set

---

## 5. Missing Number

**Overview:** Find the missing number from range [0,n].

**Example:**
Input: [3,0,1]

Output:
2

**Pattern:** Math / XOR

---

## 6. Move Zeroes

**Overview:** Move all zeroes to the end while maintaining order.

**Example:**
Input: [0,1,0,3,12]

Output:
[1,3,12,0,0]

**Pattern:** Two Pointers

---

## 7. Maximum Consecutive Ones

**Overview:** Find the maximum number of consecutive 1s.

**Example:**
Input: [1,1,0,1,1,1]

Output:
3

**Pattern:** Traversal

---

## 8. Running Sum of 1D Array

**Overview:** Calculate cumulative sum.

**Example:**
Input: [1,2,3,4]

Output:
[1,3,6,10]

**Pattern:** Prefix Sum

---

## 9. Best Time to Buy and Sell Stock

**Overview:** Maximize profit from a single transaction.

**Example:**
Input: [7,1,5,3,6,4]

Output:
5

**Pattern:** Greedy

---

## 10. Majority Element

**Overview:** Find element appearing more than n/2 times.

**Example:**
Input: [2,2,1,1,1,2,2]

Output:
2

**Pattern:** Boyer-Moore Voting

---

## 11. Find Pivot Index

**Overview:** Find index where left sum equals right sum.

**Example:**
Input: [1,7,3,6,5,6]

Output:
3

**Pattern:** Prefix Sum

---

## 12. Squares of a Sorted Array

**Overview:** Return squares in sorted order.

**Example:**
Input: [-4,-1,0,3,10]

Output:
[0,1,9,16,100]

**Pattern:** Two Pointers

---

## 13. Sort Array By Parity

**Overview:** Place even numbers before odd numbers.

**Example:**
Input: [3,1,2,4]

Output:
[2,4,3,1]

**Pattern:** Two Pointers

---

## 14. Monotonic Array

**Overview:** Check whether array is entirely increasing or decreasing.

**Example:**
Input: [1,2,2,3]

Output:
true

**Pattern:** Observation

---

## 15. Valid Mountain Array

**Overview:** Verify mountain-shaped sequence.

**Example:**
Input: [0,3,2,1]

Output:
true

**Pattern:** Two Pointers

---

## 16. Third Maximum Number

**Overview:** Find third distinct maximum.

**Example:**
Input: [3,2,1]

Output:
1

**Pattern:** Traversal

---

## 17. Intersection of Two Arrays

**Overview:** Return common unique elements.

**Example:**
Input:
nums1 = [1,2,2,1]
nums2 = [2,2]

Output:
[2]

**Pattern:** Hashing

---

## 18. Relative Sort Array

**Overview:** Sort according to another array's order.

**Example:**
Input:
arr1 = [2,3,1,3,2,4,6,7,9,2,19]
arr2 = [2,1,4,3,9,6]

Output:
[2,2,2,1,4,3,3,9,6,7,19]

**Pattern:** Counting Sort

---

## 19. Replace Elements with Greatest Element on Right Side

**Overview:** Replace every element with the largest element on its right.

**Example:**
Input: [17,18,5,4,6,1]

Output:
[18,6,6,6,1,-1]

**Pattern:** Reverse Traversal

---

## 20. Find All Numbers Disappeared in an Array

**Overview:** Find numbers missing from range [1,n].

**Example:**
Input: [4,3,2,7,8,2,3,1]

Output:
[5,6]

**Pattern:** Array Marking

---

# Patterns Covered

| Pattern       | Problems                                                |
| ------------- | ------------------------------------------------------- |
| Hashing       | Two Sum, Contains Duplicate, Intersection               |
| Two Pointers  | Move Zeroes, Remove Duplicates, Squares of Sorted Array |
| Prefix Sum    | Running Sum, Pivot Index                                |
| Greedy        | Best Time to Buy and Sell Stock                         |
| Array Marking | Missing Numbers                                         |
| Traversal     | Maximum Consecutive Ones, Third Maximum                 |
| Sorting       | Relative Sort Array                                     |

---

## Goal

Master these problems before moving to Medium-level Array questions. Focus on understanding the pattern behind the solution rather than memorizing code.
