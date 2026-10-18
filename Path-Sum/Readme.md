# Day 11 - Path Sum

**LeetCode:** 112. Path Sum  


## Problem

I have to check whether a binary tree has a root-to-leaf path whose node values add up to the given target sum.

A leaf is a node that has no children.

## Example

**Input:** `root = [5,4,8,11,null,13,4,7,2,null,null,null,1]`

**Target Sum:** `22`

**Output:** `true`

## Approach

I used recursion to solve this problem.

First, I check whether the tree is empty. If the current node is a leaf, I compare its value with the remaining target sum.

Otherwise, I subtract the current node's value from the target sum and check both subtrees recursively. If either subtree has a valid path, I return true.

## Complexity

- **Time:** `O(n)`
- **Space:** `O(h)`, where h is the height of the tree.

## What I learned

I learned how to use recursion to check whether a root-to-leaf path has a given sum.
