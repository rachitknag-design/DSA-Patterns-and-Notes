# Bubble Sort

## Problem Link

* GFG: https://www.geeksforgeeks.org/problems/bubble-sort/1

## Difficulty

Easy

## Pattern

Sorting, Arrays

---

## Problem Summary

Given an array of integers, sort the array in **ascending order** using the Bubble Sort algorithm.

---

## Approach

### Idea

Bubble Sort works by **repeatedly comparing adjacent elements and swapping them if they are in the wrong order**.

In every pass, the **largest element "bubbles up" to the end of the array**.

After each pass, the unsorted portion of the array decreases by one.

---

### Steps

1. Traverse the array from index `0` to `n-2`.
2. Compare adjacent elements `arr[j]` and `arr[j+1]`.
3. If `arr[j] > arr[j+1]`, swap them.
4. Continue this process for the entire array.
5. Repeat the passes until the array is sorted.

---

### Example

Input

```
[5, 1, 4, 2, 8]
```

Pass 1

```
[1, 4, 2, 5, 8]
```

Pass 2

```
[1, 2, 4, 5, 8]
```

Sorted Array

```
[1, 2, 4, 5, 8]
```

---

### Time Complexity

| Case         | Complexity |
| ------------ | ---------- |
| Best Case    | O(n)       |
| Average Case | O(n²)      |
| Worst Case   | O(n²)      |

Best case occurs when the array is already sorted and we use an optimization with a **swap flag**.

---

### Space Complexity

```
O(1)
```

Bubble Sort is an **in-place sorting algorithm** and does not require extra memory.

---

## Edge Cases

* Empty array
* Single element array
* Array already sorted
* Array sorted in reverse order
* Array with duplicate elements
