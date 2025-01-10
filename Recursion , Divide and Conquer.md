# Recursion and Divide and Conquer Important Questions - 
 # Recursion Important Questions -
+ **Merge two sorted Lists**  [Easy]  (https://leetcode.com/problems/merge-two-sorted-lists/)

**Approach**  -  To merge two sorted lists 

 (i) Use two pointers to traverse both lists.
 <br>
 (ii) Compare the current nodes and add the smaller one to the result list.
 <br>
 (iii) Continue until one list is exhausted, then append the remaining nodes of the other list.

+ **Decode String** [Medium]  (https://leetcode.com/problems/decode-string/description/)

**Approach**  -  To decode a string

  (i) Use two stacks
  <br>
  (ii) One for numbers (repeat counts).
  <br>
  (iii) One for strings (partial results).
  <br>
  (iv) Traverse the string
  <br>
  (v) Push numbers and '[' onto their respective stacks.
  <br>
  (vi) Build the substring when encountering ']' by popping and repeating the string.
  <br>
  (vii) Combine all parts to get the decoded result.


# Divide and Conquer Important Questions - 

+ **Convert Sorted List to Binary Search Tree**  [Medium]  (https://leetcode.com/problems/convert-sorted-list-to-binary-search-tree/)


**Approach**  -  To convert a sorted list to a BST

 (i) Use slow and fast pointers to find the middle of the list (it becomes the root).
 <br>
 (ii) Recursively build the left subtree from the left half and the right subtree from the right half.
 <br>
 (iii) Repeat until the list is fully processed.
