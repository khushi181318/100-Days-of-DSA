# Day 07 - Maximum Depth of Binary Tree

**LeetCode:** 104. Maximum Depth of Binary Tree  


## Problem

I have to find the maximum depth of a binary tree. The depth is the number of nodes from the root to the farthest leaf node.

## Example

**Input:** `root = [3,9,20,null,null,15,7]`

**Output:** `3`

## Approach

I used recursion to solve this problem.

First, I check whether the tree is empty. If it is empty, I return 0.

Then, I calculate the depth of the left and right subtrees. Finally, I return 1 plus the greater depth of the two subtrees.

## Complexity

- **Time:** `O(n)`
- **Space:** `O(h)`, where h is the height of the tree.

## What I learned

I learned how to use recursion to find the maximum depth of a binary tree.
