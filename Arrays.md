  # Arrays Important Question - 
  + **Move Zeroes** [Easy] (https://leetcode.com/problems/move-zeroes/description/)
    
   **Approach** -  The optimal approach to solve "Move Zeroes" is the two-pointer technique:

  (i) Use one pointer (j) to track the position of the next non-zero element.
  <br>
  (ii) Traverse the array with another pointer (i).
  <br>
  (iii) Whenever you encounter a non-zero element, swap it with the element at position j and move j forward.
  <br>
  (iv) This ensures all non-zero elements are moved to the left, and zeroes naturally shift to the right.
  <br>
  (v) This approach works in O(n) time and O(1) space.
