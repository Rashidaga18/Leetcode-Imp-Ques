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

  + **Majority Element**  [Easy]  (https://leetcode.com/problems/majority-element/description/)

    **Approach** - An easy-to-implement approach to solve the "Majority Element" problem is the Hash Map/Frequency Count Method

    (i) Use a dictionary (hash map) to count the frequency of each element in the array.
    <br>
    (ii)Traverse the array and update the count of each element in the dictionary.
    <br>
    (iii)Check the counts and return the element that appears more than ⌊n/2⌋ times.
    <br>
    (iv) This method is intuitive and easy to understand, especially for beginners, but it uses O(n) time and O(n) space.
