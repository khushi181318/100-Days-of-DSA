# Day 14 - Best Time to Buy and Sell Stock

**LeetCode:** 121. Best Time to Buy and Sell Stock  


## Problem

Given an array of stock prices for different days, I have to find the maximum profit by buying on one day and selling on a later day.

## Example

**Input:** `prices = [7,1,5,3,6,4]`

**Output:** `5`

## Approach

I used a greedy approach.

I keep track of the minimum price seen so far and calculate the profit if I sell on the current day.

If the profit is greater than my previous maximum profit, I update it. I also update the minimum price whenever I find a cheaper stock price.

At the end, I return the maximum profit.

## Complexity

- **Time:** `O(n)`
- **Space:** `O(1)`

## What I learned

I learned how to find the maximum profit in one pass by tracking the minimum price and updating the best profit.
