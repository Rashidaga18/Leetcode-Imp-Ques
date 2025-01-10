# Stacks Important Questions - 
+ **Valid Parentheses**  [Easy]  (https://leetcode.com/problems/valid-parentheses/description/)

**Approach**  -  To check if parentheses are valid 

 (i) Use a stack to push opening parentheses ('(', '{', '[').
 <br>
 (ii) For each closing parenthesis (')', '}', ']'), check if it matches the top of the stack.
 <br>
 (iii) If the stack is empty at the end and all parentheses matched, the string is valid.

+ **Min Stack**  [Medium]  (https://leetcode.com/problems/min-stack/description/)

**Approach**  -  To implement a min stack

 (i) Use two stacks: one for the normal stack and another for tracking the minimum element.
 <br>
 (ii) When pushing a value, push it onto the main stack and also push the minimum of the new value and the current minimum onto the min stack.
 <br>
 (iii) When popping, pop both from the main stack and the min stack.
 <br>
 (iv) The top of the min stack always holds the current minimum

+ **Remove Duplicates Letters**  [Medium]  (https://leetcode.com/problems/remove-duplicate-letters/description/)

**Approach**  -  To remove duplicate letters 

 (i) Use a stack to build the result while maintaining the lexicographical order.
 <br>
 (ii) Traverse the string 
 <br>
 (iii) If the current character is smaller than the top of the stack and it appears later, pop the stack.
 <br>
  (iv) Push the current character onto the stack if it’s not already in the result.

+ **Longest Valid Parentheses**  [Hard]  (https://leetcode.com/problems/longest-valid-parentheses/description/)

**Approach**  -  To find the longest valid parentheses

 (i) Use a stack to store indices of unmatched parentheses.
 <br> 
 (ii) Traverse the string 
 <br>
 (iii) Push the index of '(' onto the stack.
 <br>
 (iv) For ')', pop from the stack and calculate the length of the valid substring using the current index and the new top of the stack.
 <br>
 (v) Track the maximum length.
