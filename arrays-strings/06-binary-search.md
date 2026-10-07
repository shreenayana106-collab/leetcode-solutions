# Problem: Binary Search (Easy)

**Link:** https://leetcode.com/problems/binary-search/

## Approach

We use binary search on the sorted array.

We keep two pointers, left and right, and check the middle element. If the middle element is smaller than the target, we search the right half. If it is larger, we search the left half.

If the target is found, we return its index. Otherwise, we return -1.

## Complexity

- Time: O(log n)
- Space: O(1)

## Notes

Tested the solution locally with two test cases.

1. Typical case: nums = [-1, 0, 3, 5, 9, 12], target = 9
   Output: 4

2. Edge case: nums = [5], target = 2
   Output: -1

Both test cases produced the expected output.
