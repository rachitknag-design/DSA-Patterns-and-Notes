# Selection Sort

## Problem Link

* GFG: https://www.geeksforgeeks.org/problems/selection-sort/1

## Difficulty

Easy

## Pattern

Sorting, Arrays

---

## Problem Summary

Given an array of integers, sort the array in ascending order using the **Selection Sort algorithm**.

---

## Approach

### Idea

Selection Sort repeatedly finds the **minimum element from the unsorted portion of the array** and places it at the beginning.

### Steps

1. Start from index `0`.
2. Assume the current index is the minimum.
3. Traverse the remaining array to find the actual minimum element.
4. Swap the minimum element with the current index.
5. Repeat the process for the remaining elements.

### Time Complexity

O(n²)

### Space Complexity

O(1)

---

## Edge Cases

* Empty array
* Single element array
* Array already sorted
* Array with duplicate elements
