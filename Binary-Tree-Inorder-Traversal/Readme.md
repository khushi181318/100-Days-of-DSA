# Day 04 - Binary Tree Inorder Traversal

**LeetCode:** 94. Binary Tree Inorder Traversal  


## Problem

I am given the root of a binary tree.

I have to return the values of the nodes in inorder traversal.

Inorder traversal means:

`Left -> Root -> Right`

## Example

Input:

`[1,null,2,3]`

Output:

`[1,3,2]`

## Approach

I used recursion to traverse the tree.

First, I visit the left subtree.
Then I store the current node value.
Finally, I visit the right subtree.

So the order is:

`Left -> Root -> Right`

If the root is null, I simply return.

## Complexity

- Time: `O(n)`
- Space: `O(n)`

## What I learned

I learned how inorder traversal works in a binary tree and how recursion can be used to visit all the nodes in the required order.
