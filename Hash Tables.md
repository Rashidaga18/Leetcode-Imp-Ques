# Hash Tables Important Questions - 

+ **Isomorphic Strings**  [Easy]  (https://leetcode.com/problems/isomorphic-strings/description/)

**Approach** - The optimal approach for "Isomorphic Strings" is to use Hash Maps

 (i) Create two hash maps (or dictionaries):
 <br>
 + One to map characters from string s to t.
 + Another to map characters from t to s.

 (ii)  Traverse both strings simultaneously:
 + Check if the mapping is consistent for both directions.
 + If there's a mismatch, the strings are not isomorphic.
   
 (iii) Return true if the traversal completes without conflicts

+ **Contains Duplicate II**  [Easy]  (https://leetcode.com/problems/contains-duplicate-ii/description/)

**Approach** -The optimal approach for "Contains Duplicate II" is to use a Sliding Window with Hash Map

  (i) Use a hash map to store the most recent index of each element.
  <br>
  (ii) As you traverse the array, check if the current element exists in the map and if the difference between indices is ≤ k.
  <br>
  (iii) If yes, return True. Otherwise, update the index in the hash map.
  <br>
  (iv) If the loop completes without finding such a pair, return False.

+ **Group Anagrams**  [Medium]  (https://leetcode.com/problems/group-anagrams/description/)

**Approach** - The optimal approach for "Group Anagrams" is to use Hashing

(i) For each string, sort the characters and use the sorted string as the key in a hash map.
<br>
(ii) Group strings with the same sorted key together.
<br>
(iii) Return the values of the hash map, which will be the grouped anagrams.

+ **Encode and Decode TinyURL**  [Medium]  (https://leetcode.com/problems/encode-and-decode-tinyurl/description/)

**Approach** - The optimal approach for "Encode and Decode TinyURL" is to use a Hash Map

(i) Encoding:

 + Generate a unique short key (e.g., random string, hash, or incremental counter).
 + Map the short key to the original URL in a hash map.

 (ii) Decoding:

 + Use the short key to retrieve the original URL from the hash map.

+ **Longest Consecutive Sequence**  [Medium]  (https://leetcode.com/problems/longest-consecutive-sequence/description/)

**Approach** - The optimal approach for "Longest Consecutive Sequence" is to use a Hash Set

 (i) Add all numbers to a hash set for O(1) lookups.
 <br>
 (ii) Traverse the array:
  + If the current number is the start of a sequence (i.e., num - 1 is not in the set), count the length of the sequence by checking consecutive numbers (num + 1, num + 2, etc.) in the set.
    
 (iii) Track the maximum sequence length during traversal.
