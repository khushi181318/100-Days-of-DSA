# Day 09 - Balanced Binary Tree

**LeetCode:** 110. Balanced Binary Tree  


## Problem

I have to check whether a binary tree is height-balanced.

A tree is height-balanced if the heights of the left and right subtrees differ by at most 1 at every node.

## Example

**Input:** `root = [3,9,20,null,null,15,7]`

**Output:** `true`

## Approach

I used recursion to calculate the height of each subtree.

If the tree is empty, I return 0. I calculate the left and right subtree heights and check their difference.

If the difference is greater than 1, I return -1 to indicate that the tree is unbalanced. I also stop if a subtree is already unbalanced.

Finally, I return true if the height function does not return -1.

## Complexity

- **Time:** `O(n)`
- **Space:** `O(h)`, where h is the height of the tree.

## What I learned

I learned how to check whether a binary tree is height-balanced using recursion.
