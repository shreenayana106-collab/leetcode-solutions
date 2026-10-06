# Problem: Two Sum (Easy)

**Link:** https://leetcode.com/problems/two-sum/

## Approach

We check every possible pair of numbers using two nested loops. If the sum of two numbers is equal to the target, we print the indices of those two numbers.

## Complexity

- Time: O(n²)
- Space: O(1)

## Notes

Tested the solution locally with two test cases.

1. Typical case: nums = [2, 7, 11, 15], target = 9
2. Edge case: nums = [3, 3], target = 6

Both test cases produced the expected output [0, 1].
