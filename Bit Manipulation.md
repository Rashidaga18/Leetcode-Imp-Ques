# Bit Manipulation Important Ques -
+ **Single Number**  [Easy]  (https://leetcode.com/problems/single-number/description/)

**Approach** - The optimal approach for "Single Number" is to use the XOR Method

 (i) Initialize a variable result = 0.
 <br>
 (ii) Traverse the array and XOR every element with result.
 <br>
 (iii) After the traversal, result will hold the single number because
 <br>
 (iv) XOR of a number with itself is 0 (e.g.,a⊕a=0).
 <br>
 (v) XOR of a number with 0 is the number itself (e.g., a⊕0=a).
 <br>
 (vi) All numbers appearing twice cancel out, leaving the single number.
 <br>
 (vii) This approach works in O(n) time and uses O(1) space.

+ **Counting Bits**  [Easy]  (https://leetcode.com/problems/counting-bits/description/)

**Approach** - The optimal approach for "Counting Bits" is to use Dynamic Programming with Bit Shifts

 (i) Use the relation:  **countBits(i)=countBits(i>>1)+(i&1)**
 <br>
(ii) i >> 1 shifts i right by one bit (essentially dividing by 2).
<br>
(iii) i & 1 checks if the least significant bit is 1.
<br>
(iv) Initialize an array dp where dp[i] stores the number of 1's in the binary representation of i.
<br>
(v) Iterate from 0 to n to compute dp[i] using the above formula.
<br>
(vi) This approach works in O(n) time and uses O(n) space.


+ **Single Number III**  [Medium]  (https://leetcode.com/problems/single-number-iii/description/)

**Approach** - The optimal approach for "Single Number III" is

  (i) XOR all numbers to get xor = x ⊕ y, where x and y are the unique numbers.
  <br>
  (ii) Find the rightmost set bit in xor to distinguish x and y.
  <br>
  (iii) Split numbers into two groups based on this bit and XOR each group to find x and y.
  <br>






