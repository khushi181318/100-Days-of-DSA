# Day 10 - Minimum Depth of Binary Tree

**LeetCode:** 111. Minimum Depth of Binary Tree  


## Problem

I have to find the minimum depth of a binary tree. It is the number of nodes from the root to the nearest leaf node.

A leaf node is a node that has no children.

## Example

**Input:** `root = [3,9,20,null,null,15,7]`

**Output:** `2`

## Approach

I used recursion to solve this problem.

If the tree is empty, I return 0. If one child is missing, I calculate the depth using the other subtree.

If both children exist, I find the smaller depth and add 1 for the current node.

## Complexity

- **Time:** `O(n)`
- **Space:** `O(h)`, where h is the height of the tree.

## What I learned

I learned how to find the shortest path from the root to a leaf using recursion and why a missing child needs special handling.
