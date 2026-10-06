# Problem: Reverse a String (Easy)

**Link:** https://leetcode.com/problems/reverse-string/

## Approach

We use two pointers, one at the beginning of the string and one at the end.

We swap the characters at these positions and move both pointers toward the center. We continue until the pointers meet.

## Complexity

- Time: O(n)
- Space: O(1)

## Notes

Tested the solution locally with two test cases.

1. Typical case: str = "hello"
   Output: "olleh"

2. Edge case: str = "a"
   Output: "a"

Both test cases produced the expected output.
