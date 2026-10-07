# Day 03 - Merge Sorted Array

**LeetCode:** 88. Merge Sorted Array  


## Problem

I am given two sorted arrays, nums1 and nums2.

I have to merge nums2 into nums1 and keep the final array sorted.

The extra spaces in nums1 are already available at the end.

## Example

Input:

`nums1 = [1,2,3,0,0,0]`

`nums2 = [2,5,6]`

Output:

`[1,2,2,3,5,6]`

## Approach

I used three pointers.

- `i` points to the last actual element of nums1.
- `j` points to the last element of nums2.
- `k` points to the last position of nums1.

 Now,I compared the elements from the end and placed the bigger element at position `k`.

This way I don't overwrite the existing elements of nums1.

## Complexity

- Time: `O(m + n)`
- Space: `O(1)`

## What I learned

I learned how to use the two-pointer approach and why merging from the end is useful when the first array has extra space.
