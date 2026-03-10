# Two Pointers Pattern

The **Two Pointers** technique is commonly used when working with arrays or strings.

Instead of using nested loops, two pointers allow us to traverse a data structure from different directions or positions.

This often reduces the time complexity from **O(n²)** to **O(n)**.

## When to Use Two Pointers

The pattern is useful when:

- the input is sorted
- we need to compare pairs of elements
- we want to shrink or expand a search space
- we want to avoid nested loops

## Example Problem

Find two numbers in a sorted array that add up to a target value.

### Approach

Use two pointers:

- one pointer starts from the beginning
- one pointer starts from the end

Move pointers based on the current sum.

### Example

Input:

nums = [1, 2, 4, 6, 10]  
target = 8

Steps:

1. left = 1, right = 10 → sum = 11 → move right
2. left = 1, right = 6 → sum = 7 → move left
3. left = 2, right = 6 → sum = 8 → solution found

## Time Complexity

O(n)

## Key Insight

Two pointers help eliminate unnecessary comparisons by narrowing the search space from both ends.

Recognizing when to apply this pattern is an important step in efficient problem solving.

---

### CodeWithIshwar

Engineering thinking for developers.

Created by **Ishwar Chandra Tiwari**
