# Monotonic Important Questions - 

# Montonic Stack Important Questions - 

+ **Daily Temperatures**  [Medium]  (https://leetcode.com/problems/daily-temperatures/description/)

**Approach**  -  To solve daily temperatures 

 (i) Use a stack to track indices of temperatures in decreasing order.
 <br>
 (ii) For each temperature
 <br>
 (iii) Pop from the stack until a higher temperature is found.
 <br>
 (iv) For each pop, calculate the difference in indices to determine how many days to wait.
 <br>
 (v) Push the current index onto the stack.

+ **Largest Rectangle in Histogram**  [Hard]  ( https://leetcode.com/problems/largest-rectangle-in-histogram/description/)

**Approach**  -  To find the largest rectangle in histogram 

 (i) Use a stack to keep track of bar indices in increasing order of height.
 <br>
 (ii) Traverse the histogram
 <br>
 (iii) For each bar, while the stack is not empty and the current bar is shorter than the bar at the top of the stack, pop from the stack and calculate the area.
 <br>
 (iv) Push the current bar index onto the stack.
 <br>
 (v) Calculate the area for remaining bars in the stack after traversal.


# Montonic Queue Important Questions - 

+ **Sliding Window Maximum**  [Hard] (https://leetcode.com/problems/sliding-window-maximum/description/)

**Approach**  -  To find the sliding window maximum 

 (i) Use a deque (double-ended queue) to store indices of elements in the current window, maintaining the order of maximum values.
 <br>
 (ii) Traverse the array 
 <br>
 (iii) Remove indices from the front of the deque if they are outside the window.
 <br>
 (iv) Remove indices from the back of the deque if the current element is greater than the element at those indices.
 <br>
 (v) Add the current element's index to the deque.
 <br>
 (vi) The front of the deque always holds the index of the maximum element for the current window.
