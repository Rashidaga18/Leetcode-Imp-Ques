# Prefix Sum Important Questions -

+ **Range Sum Query - Immutable**  [Easy]  (https://leetcode.com/problems/range-sum-query-immutable/description/)

**Approach** - The optimal approach for "Range Sum Query - Immutable" is to use Prefix Sum

  (i) Precompute Prefix Sums:
  <br>
  + Create an array prefix_sum where each entry at index i stores the sum of all elements from the start up to index i.
  + This can be computed as:  prefix_sum[i]=prefix_sum[i−1]+nums[i]
    
  (ii) Answer Queries in O(1):
  <br>
   + For a query  [i,j], calculate the range sum as: Range Sum=prefix_sum[j]−prefix_sum[i−1]
   + i=0, the sum is simply prefix_sum[j].
---
+ **SubArray Sum Equals K**  [Medium]  (https://leetcode.com/problems/subarray-sum-equals-k/description/)

**Approach**  -  Use a hash map to track prefix sums.

  (i) For each element, update current_sum and check if current_sum - k exists in the map.
  <br>
  (ii) If yes, add its frequency to the count.
  <br>
  (iii) Update the map with the current prefix sum

+ **Contiguous Array**  [Medium]  (https://leetcode.com/problems/contiguous-array/description/)

**Approach**  - Replace 0s with -1s. Use a hash map to track the first occurrence of each prefix sum.

  (i) If prefix_sum repeats, update max_length as the difference between the current and stored index.
  <br>
  (ii) If prefix_sum is 0, update max_length to include the subarray from the start.
