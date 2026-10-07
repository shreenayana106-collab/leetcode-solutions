# Problem: Move Zeroes (Easy)

**Link:** https://leetcode.com/problems/move-zeroes/

## Approach

We keep a position pointer for the next non-zero element.

We first move all non-zero elements to the beginning of the array while maintaining their original order. Then we fill the remaining positions with zeroes.

## Complexity

- Time: O(n)
- Space: O(1)

## Notes

Tested the solution locally with two test cases.

1. Typical case: nums = [0, 1, 0, 3, 12]
   Output: [1, 3, 12, 0, 0]

2. Edge case: nums = [0, 0, 0]
   Output: [0, 0, 0]

Both test cases produced the expected output.
