# Explanation

## Brute Force Approach

Check every pair of numbers in the array.

Time Complexity: O(n²)

This approach works but is inefficient for large inputs.

---

## Optimized Approach

Use a **HashMap** to store numbers and their indices.

### Steps

1. Iterate through the array.
2. Compute the complement:

   target - nums[i]

3. Check if the complement exists in the map.
4. If yes → return the indices.
5. Otherwise store the current value in the map.

---

## Complexity

Time Complexity: O(n)  
Space Complexity: O(n)

---

## Key Insight

Recognizing the correct **data structure** often simplifies algorithm problems.

A HashMap allows constant-time lookups and avoids unnecessary comparisons.

---

### CodeWithIshwar

Engineering thinking for developers.

Created by **Ishwar Chandra Tiwari**
