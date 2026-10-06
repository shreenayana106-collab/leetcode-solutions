# Problem: Best Time to Buy and Sell Stock (Easy)

**Link:** https://leetcode.com/problems/best-time-to-buy-and-sell-stock/

## Approach

We keep track of the minimum price seen so far.

For each price, we calculate the profit that would be made by selling at that price. We keep the maximum profit found.

## Complexity

- Time: O(n)
- Space: O(1)

## Notes

Tested the solution locally with two test cases.

1. Typical case: prices = [7, 1, 5, 3, 6, 4]
   Output: 5

2. Edge case: prices = [7, 6, 4, 3, 1]
   Output: 0

Both test cases produced the expected output.
