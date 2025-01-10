# Kadane's Algorithm Important Questions - 

+ **Maximum SubArray**  [Medium]  (https://leetcode.com/problems/maximum-subarray/description/)

**Approach** - Use Kadane's Algorithm:

 (i) Initialize current_sum and max_sum to 0.
 <br>
 (ii) Traverse the array 
 <br>
 (iii) Add the current element to current_sum.
 <br>
 (iv) If current_sum becomes negative, reset it to 0.
 <br>
 (v) Update max_sum with the maximum of max_sum and current_sum.

+ **Maximum Product SubArray**  [Medium]  (https://leetcode.com/problems/maximum-product-subarray/description/)

**Approach**  -  Use Kadane's Algorithm with two variables:

  (i) Track both the maximum product (max_prod) and minimum product (min_prod) up to the current index, as the minimum product might become the maximum if multiplied by a negative number.
  <br>
  (ii) At each step, update max_prod and min_prod, considering the current element, its product with the previous max_prod, and min_prod.
