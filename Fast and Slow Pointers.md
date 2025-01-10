# Fast and Slow Pointers Important Questions - 

+ **Middle of the Linked List**  [Easy]  (https://leetcode.com/problems/middle-of-the-linked-list/description/)

**Approach**  -  To find the middle of a linked list

 (i) Use two pointers: slow and fast.
 <br>
 (ii) Move slow one step at a time, and fast two steps at a time.
 <br>
 (iii) When fast reaches the end, slow will be at the middle.

+ **Linked List Cycle II**  [Medium]  (https://leetcode.com/problems/linked-list-cycle-ii/description/)

**Approach**  -  To detect the cycle in a linked list and find the starting node of the cycle

 (i) Use Floyd's Tortoise and Hare algorithm to detect the cycle (using slow and fast pointers).
 <br>
 (ii) Once a cycle is detected, move one pointer to the head and keep the other at the meeting point.
 <br>
 (iii) Move both pointers one step at a time. The node where they meet is the start of the cycle.
