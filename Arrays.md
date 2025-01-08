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

    
 + **Product of Array Except Self**  [Medium] (https://leetcode.com/problems/product-of-array-except-self/description/)

   **Approach**  - The optimal approach for "Product of Array Except Self" is to use prefix and suffix products

    (i) Compute the prefix product for each element (product of all elements to the left).
   <br>
    (ii) Compute the suffix product for each element (product of all elements to the right).
   <br>
    (iii) Multiply the prefix and suffix products for each element to get the result.
   <br>
    (iv) This approach works in O(n) time and uses O(1) extra space

+ **Best Time to Buy and Sell Stock II**  [Medium] (https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/description/)

  **Approach** - The optimal approach for "Best Time to Buy and Sell Stock II" is the Greedy Method

  (i) Traverse the array of prices.
  <br>
  (ii) Whenever the price on the current day is greater than the price on the previous day, add the difference to the profit.
  <br>
  (iii) This ensures you capture all the upward trends (buying at the lowest point and selling at the highest point for each segment).
  <br>
  (iv) This approach works in O(n) time and is simple to implement.

+ **First Missing Positive**  [Hard] (https://leetcode.com/problems/first-missing-positive/description/)

  **Approach** - The optimal approach for "First Missing Positive" is the Cyclic Sort Method

  (i) Place each number in its correct position if it falls within the range [1, n] (where n is the array size). For example, 1 should be at index 0, 2 at index 1, and so on.
  <br>
  (ii) Traverse the array:
  <br>
  (iii) If a number is not in its correct position (i.e., nums[i] != i + 1), that's the first missing positive.
  <br>
  (iv) If all numbers are in the correct position, the missing positive is n + 1.
  <br>
  (v) This approach works in O(n) time and O(1) space.
