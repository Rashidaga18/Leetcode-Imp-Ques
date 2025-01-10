# Sliding Window Important Questions -
# Sliding Window - Fixed Size 

+ **Find All Anagrams in a String**  [Medium]  (https://leetcode.com/problems/find-all-anagrams-in-a-string/description/)

**Approach**  -  Use a sliding window and hash maps to compare character frequencies in the current window of s with p.

  (i) Slide the window across s, updating counts for entering and exiting characters.
  <br>
  (ii) If the counts match, record the starting index.

+ **Permutation in a String**  [Medium]  (https://leetcode.com/problems/permutation-in-string/description/)

**Approach**  - Use a sliding window with hash maps to compare character frequencies in s1 and the current window of s2.

  (i) Slide the window across s2, updating counts for entering and exiting characters.
  <br>
  (ii) If the counts match, return True. Otherwise, return False.

# Sliding Window - Dynamic Size

+ **Longest Substring Without Repeating Characters**  [Medium]  (https://leetcode.com/problems/longest-substring-without-repeating-characters/description/)

**Approach** - Use a sliding window with a hash set to track characters in the current window.

  (i) Expand the window by moving the right pointer and add characters to the set.
  <br>
  (ii) If a character repeats, move the left pointer to remove the duplicate.
  <br>
 (ii) Track the maximum window size. 

+ **Minimum Window Substring**  [Hard]  (https://leetcode.com/problems/minimum-window-substring/description/)

**Approach** - Use a sliding window with two pointers and a hash map to track the characters of the target string t.

 (i) Expand the window by moving the right pointer and update character counts.
 <br>
 (ii) Contract the window by moving the left pointer when all characters of t are found.
 <br>
 (ii) Track the minimum window that contains all characters of t.
