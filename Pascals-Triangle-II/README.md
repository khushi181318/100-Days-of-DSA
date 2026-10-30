# Day 13 - Pascal's Triangle II

**LeetCode:** 119. Pascal's Triangle II  


## Problem

I have to return the specific row of Pascal's Triangle using the given 0-indexed rowIndex.

Each number is calculated by adding the two numbers directly above it.

## Example

**Input:** `rowIndex = 3`

**Output:** `[1,3,3,1]`

## Approach

I used a vector to solve this problem.

First, I initialize a vector of size `rowIndex + 1` with all values as 1.

Then, I use nested loops to calculate the middle elements. I update the vector from right to left so that the previous values are not overwritten.

Finally, I return the required row.

## Complexity

- **Time:** `O(rowIndex²)`
- **Space:** `O(rowIndex)`

## What I learned

I learned how to generate a specific row of Pascal's Triangle using a single vector and update its values from right to left.
