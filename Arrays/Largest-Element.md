# Largest Element in Array

## Problem Link
- GFG: https://www.geeksforgeeks.org/problems/largest-element-in-array4009/1

## Difficulty
Easy

## Pattern
Array Traversal

---

## Problem Summary
Find the largest element present in the array.

---

## **Brute Force Approach**

### Idea
Sort the array and return the last element.

### Steps
1. Sort the array.
2. The last element will be the largest element.

### Time Complexity
O(n log n)

### Space Complexity
O(1) (if in-place sorting)

---

## **Optimal Approach**

### Idea
Traverse the array and keep track of the maximum element.

### Steps
1. Initialize `max` with the first element.
2. Traverse the array from index `1` to `n-1`.
3. If `arr[i] > max`, update `max`.
4. After traversal, `max` will be the largest element.

### Time Complexity
O(n)

### Space Complexity
O(1)

---

## Edge Cases
- Single element array
- Negative numbers
- All elements equal

## Key Learning
Sorting can solve many problems but often there exists a better solution using a single traversal.
