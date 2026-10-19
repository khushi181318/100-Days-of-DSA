# Day 12 - Pascal's Triangle

**LeetCode:** 118. Pascal's Triangle  


## Problem

I have to generate the first `numRows` of Pascal's Triangle.

Each row starts and ends with 1. The middle numbers are calculated by adding the two numbers directly above them.

## Example

**Input:** `numRows = 5`

**Output:** `[[1],[1,1],[1,2,1],[1,3,3,1],[1,4,6,4,1]]`

## Approach

I used nested loops to solve this problem.

First, I create each row with all values set to 1. Then, I calculate the middle values by adding the two adjacent numbers from the previous row.

After completing each row, I add it to the triangle and return the final result.

## Complexity

- **Time:** `O(numRows²)`
- **Space:** `O(numRows²)` to store the triangle.

## What I learned

I learned how to use nested loops and a previous row's values to generate Pascal's Triangle.
