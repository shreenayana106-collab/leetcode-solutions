# Problem: Longest Common Prefix (Easy)

**Link:** https://leetcode.com/problems/longest-common-prefix/

## Approach

We compare the characters at the same position in all strings.

Starting from the first character, we continue while every string has the same character. When a different character is found, the common prefix ends.

## Complexity

- Time: O(n × m)
- Space: O(1)

## Notes

Tested the solution locally with two test cases.

1. Typical case: ["flower", "flow", "flight"]
   Output: "fl"

2. Edge case: ["dog", "racecar", "car"]
   Output: ""

Both test cases produced the expected output.
