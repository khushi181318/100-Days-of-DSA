# Day 06 - Symmetric Tree

**LeetCode:** 101. Symmetric Tree  


## Problem

I have to check whether a binary tree is symmetric around its center.

A symmetric tree should look the same on its left and right sides.

## Example

**Input:** `root = [1,2,2,3,4,4,3]`

**Output:** `true`

## Approach

I used recursion to solve this problem.

I compare the left and right subtrees like mirror images. The values should be equal, and their child nodes should also match in the opposite order.

If both nodes are empty, they are symmetric. If only one is empty or their values are different, they are not symmetric.

## Complexity

- **Time:** `O(n)`
- **Space:** `O(h)`, where h is the height of the tree.

## What I learned

I learned how to use recursion to check whether two subtrees are mirror images of each other.
