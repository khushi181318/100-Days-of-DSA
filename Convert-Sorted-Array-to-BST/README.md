# Day 08 - Convert Sorted Array to Binary Search Tree

**LeetCode:** 108. Convert Sorted Array to Binary Search Tree  


## Problem

I have to convert a sorted array into a height-balanced binary search tree.

A height-balanced tree has left and right subtrees whose heights differ by at most 1 at every node.

## Example

**Input:** `nums = [-10,-3,0,5,9]`

**Output:** `[0,-3,9,-10,null,5]`

## Approach

I used recursion to solve this problem.

First, I select the middle element of the array as the root. Then I create the left subtree using the left half of the array and the right subtree using the right half.

I repeat this process until all elements are added to the tree.

## Complexity

- **Time:** `O(n)`
- **Space:** `O(log n)` for the recursion stack in a balanced tree, excluding the output tree.

## What I learned

I learned how to convert a sorted array into a height-balanced binary search tree using recursion.
