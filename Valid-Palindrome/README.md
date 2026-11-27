# Day 15 - Valid Palindrome

**LeetCode:** 125. Valid Palindrome  


## Problem

The string contains letters, numbers, spaces, and special characters. I have to check whether it reads the same forward and backward after ignoring spaces and special characters and converting uppercase letters to lowercase.

## Example

**Input:** `s = "A man, a plan, a canal: Panama"`

**Output:** `true`

## Approach

I used the two-pointer approach.

I take one pointer from the beginning and another from the end of the string. I skip the characters that are not letters or numbers. Then I compare both characters after converting them to lowercase.

If they are different, I return `false`. If they match, I move both pointers toward the middle. If all characters match, I return `true`.

## Complexity

- **Time:** `O(n)`
- **Space:** `O(1)`

## What I learned

I learned how to use two pointers to check a palindrome and how to ignore unwanted characters while comparing a string.
