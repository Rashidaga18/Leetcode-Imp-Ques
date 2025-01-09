# Two Pointers Important Question - 
+ **Two Sum II - Input Array Is Sorted**  [Medium]  (https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/description/)

**Approach** - The optimal approach for "Two Sum II - Input Array Is Sorted" is to use the Two-Pointer Technique 

  (i) Use two pointers: one starting at the beginning (left) and the other at the end (right) of the array.
  <br>
  (ii) Compute the sum of the elements at the two pointers:
   + If the sum equals the target, return the indices.
   + If the sum is less than the target, move the left pointer forward.
     
  (iii) If the sum is greater than the target, move the right pointer backward.
  <br>
  (iv) Repeat until the pointers meet.

  + **Container with most water**  [Medium]  (https://leetcode.com/problems/container-with-most-water/description/)

**Approach** - The optimal approach for "Container With Most Water" is the Two-Pointer Technique

 (i) Place two pointers, one at the beginning (left) and one at the end (right) of the array.
 <br>
 (ii) Calculate the area using the formula: Area=min(height[left],height[right])×(right−left)
 <br>
(iii) Track the maximum area encountered.
<br>
 (iv) Move the pointer pointing to the shorter height inward to potentially find a taller boundary and increase the area.
 <br>
 (v) Repeat until the pointers meet.

+ **3Sum**  [Medium]  (https://leetcode.com/problems/3sum/description/)

**Approach** - The optimal approach for "3Sum" is to use Two Pointers with Sorting

 (i) Sort the Array:

  + Sort the input array to enable two-pointer traversal.
    
 (ii) Iterate Over the Array:

 + Fix one element as the first number in the triplet.
+ Use two pointers (left and right) to find the other two numbers such that their sum equals the negative of the fixed number.
  
 (iii) Avoid Duplicates:

  + Skip duplicate values for the fixed number and during the two-pointer traversal to avoid repeated triplets.
    
 (iv) Move Pointers:

+ If the sum of the triplet is less than zero, move the left pointer forward.
+ If the sum is greater than zero, move the right pointer backward.
+ If the sum is zero, record the triplet and adjust both pointers to continue searching.

+ **Trapping Rain Water**  [Hard]  (https://leetcode.com/problems/trapping-rain-water/description/)

**Approach**  - Use two pointers (left and right) to traverse the array.

  (i) Track left_max and right_max to store the highest walls on each side.
  <br>
  (ii) Calculate water trapped as the difference between the current height and the minimum of left_max or right_max.
  <br>
  (iii) Move the pointer with the smaller height inward.
