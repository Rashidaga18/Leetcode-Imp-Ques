# Strings Important Question -
+ **Is Subsequence**  [Easy]  (https://leetcode.com/problems/is-subsequence/description/)

**Approach** - The optimal approach for "Is Subsequence" is the Two-Pointer Method

 (i) Use two pointers: one for the subsequence string (s) and one for the main string (t).
 <br>
 (ii) Traverse both strings:
 <br>
 (iii) If the characters at both pointers match, move the pointer in s forward.
 <br>
 (iv) Always move the pointer in t forward.
 <br>
 (v) If the pointer for s reaches the end, s is a subsequence of t.
 <br>
 (vi) This approach works in O(n + m) time, where n is the length of t and m is the length of s, and uses O(1) space

+ **Valid Palindrome**  [Easy]  (https://leetcode.com/problems/valid-palindrome/description/)

**Approach** - The optimal approach for "Valid Palindrome" is the Two-Pointer Method 

  (i) Use two pointers: one at the start (left) and one at the end (right) of the string.
  <br>
  (ii) While left < right:
  <br>
  (iii) Skip non-alphanumeric characters by moving left or right inward as needed.
  <br>
  (iv) Compare the characters at left and right (case-insensitive). If they differ, the string is not a palindrome.
  <br>
  (v) If the entire string is traversed without mismatches, it is a valid palindrome.
  <br>
  (vi) This approach works in O(n) time and uses O(1) space.

+ **Reverse Words in a String**  [Medium]  (https://leetcode.com/problems/reverse-words-in-a-string/description/)

**Approach** - The optimal approach for "Reverse Words in a String" is to use Split and Reverse 

  (i) Split the string into words by spaces, ignoring extra spaces.
  <br>
  (ii) Reverse the order of the words.
  <br>
  (iii) Join the reversed words with a single space.
  <br>
  (iv) This approach works in O(n) time and uses O(n) space for the intermediate word list.






