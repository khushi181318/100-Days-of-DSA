# Day 05 - Same Tree

**LeetCode:** 100. Same Tree  


## Problem

I am given two binary trees and have to check whether they are the same or not.

Both trees should have the same structure and the same node values.

## Example

Input:

`p = [1,2,3]`

`q = [1,2,3]`

Output: `true`

## Approach

I used recursion to compare the two trees.

If both nodes are empty, I return true.

If only one node is empty or their values are different, I return false.

Otherwise, I compare their left and right subtrees. Both sides should be the same.

## Complexity

- Time: `O(n)`
- Space: `O(h)`, where h is the height of the tree.

## What I learned

I learned how to compare two binary trees using recursion and check whether their structure and values are the same.
