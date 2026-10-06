# Day 02 - Remove Duplicates from Sorted List

**LeetCode:** 83. Remove Duplicates from Sorted List  
**Difficulty:** Easy

## Problem

I am given a sorted linked list.

I have to remove the duplicate values so that each value appears only once.

### Example

Input:

`[1,1,2,3,3]`

Output:

`[1,2,3]`

## Approach

Since the linked list is already sorted, duplicate values will be next to each other.So,

I used a pointer called `current` to go through the list and

If the current node and the next node have the same value, I skip the next node.

Otherwise, I move the pointer to the next node.

## Complexity

- Time: `O(n)`
- Space: `O(1)`

## What I learned

I learned how to traverse a linked list and remove a node by changing the `next` pointer.
