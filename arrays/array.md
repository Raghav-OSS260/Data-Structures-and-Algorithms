# Arrays

## What is an Array?

An array is a linear data structure that stores elements of the same data type in contiguous memory locations.

Example:

```cpp
int arr[5] = {10, 20, 30, 40, 50};
```

Here:

* `arr[0] = 10`
* `arr[1] = 20`
* `arr[2] = 30`
* `arr[3] = 40`
* `arr[4] = 50`

Arrays use **0-based indexing**.

---

## Why Learn Arrays?

Arrays are the foundation of Data Structures and Algorithms.

Many important topics are built upon arrays:

* Two Pointers
* Sliding Window
* Prefix Sum
* Binary Search
* Sorting Algorithms
* Dynamic Programming

Mastering arrays makes advanced DSA topics much easier.

---

## Array Operations

### 1. Traversal

Visiting every element of the array.

```cpp
for(int i = 0; i < n; i++)
{
    cout << arr[i] << " ";
}
```

Time Complexity: O(n)

---

### 2. Insertion

Adding a new element at a specific position.

Time Complexity: O(n)

---

### 3. Deletion

Removing an element from a specific position.

Time Complexity: O(n)

---

### 4. Searching

#### Linear Search

```cpp
for(int i = 0; i < n; i++)
{
    if(arr[i] == target)
        return i;
}
```

Time Complexity: O(n)

#### Binary Search (Sorted Array)

Time Complexity: O(log n)

---

## Advantages of Arrays

* Fast access using index
* Easy to traverse
* Memory efficient
* Foundation of many algorithms

---

## Disadvantages of Arrays

* Fixed size
* Insertion and deletion are costly
* Wastage of memory if size is overestimated

---

## Time Complexities

| Operation | Complexity |
| --------- | ---------- |
| Access    | O(1)       |
| Search    | O(n)       |
| Insert    | O(n)       |
| Delete    | O(n)       |
| Traverse  | O(n)       |

---

## Common Interview Questions

### Easy

* Two Sum
* Remove Duplicates from Sorted Array
* Best Time to Buy and Sell Stock
* Move Zeroes

### Medium

* 3Sum
* Rotate Array
* Product of Array Except Self
* Container With Most Water

### Hard

* Trapping Rain Water
* First Missing Positive
* Median of Two Sorted Arrays

---

## Key Takeaway

Arrays are the starting point of DSA. Before learning Linked Lists, Trees, Graphs, or Dynamic Programming, develop strong command over array traversal, searching, insertion, deletion, and common patterns such as Two Pointers, Sliding Window, and Prefix Sum.
