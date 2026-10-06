# Problem: Valid Anagram (Easy)

**Link:** https://leetcode.com/problems/valid-anagram/

## Approach

We use an array of 26 integers to count the frequency of each lowercase letter.

First, we increase the count for every character in the first string. Then, we decrease the count for every character in the second string.

If all counts become zero, both strings contain the same characters with the same frequencies, so they are anagrams.

## Complexity

- Time: O(n)
- Space: O(1)

## Notes

Tested the solution locally with two test cases.

1. Typical case: s = "anagram", t = "nagaram"
   Output: true

2. Edge case: s = "a", t = "a"
   Output: true

Both test cases produced the expected output.
