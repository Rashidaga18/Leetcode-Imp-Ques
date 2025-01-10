# Linked List Important Questions - 

+ **Intersection of Two Linked Lists**  [Easy]  (https://leetcode.com/problems/intersection-of-two-linked-lists/description/)

**Approach** - To find the intersection of two linked lists 

 (i) Calculate the lengths of both lists.
 <br>
(ii) Align the starting points by advancing the longer list by the difference in lengths.
<br>
 (iii) Traverse both lists simultaneously, comparing nodes. The first common node is the intersection.

+ **Remove Nth node from End of List**  [Medium]  (https://leetcode.com/problems/remove-nth-node-from-end-of-list/description/)

**Approach**  -  To remove the N-th node from the end of a linked list

  (i) Use two pointers, fast and slow.
  <br>
  (ii) Move fast N steps ahead.
  <br>
  (iii) Move both fast and slow one step at a time until fast reaches the end.
  <br>
  (iv) Slow will be at the node before the N-th node from the end. Remove the N-th node.

+ **Swap Nodes in Pairs**  [Medium]  (https://leetcode.com/problems/swap-nodes-in-pairs/description/)

**Approach**  -  To swap nodes in pairs

 (i) Traverse the list in pairs, swapping adjacent nodes.
 <br>
 (ii) Adjust the next pointers of the swapped nodes to maintain the list structure

+ **Rotate List**  [Medium]  (https://leetcode.com/problems/rotate-list/description/)

**Approach**  -  To rotate a linked list 

 (i) Find the length of the list.
 <br>
 (ii) Make the list circular by connecting the last node to the head.
 <br>
(iii) Find the new head by moving the pointer to the (length - k % length)-th node.
<br>
 (iv) Break the circular connection by setting the new tail's next pointer to null.


+ **Add Two Numbers**  [Medium]  (https://leetcode.com/problems/add-two-numbers/description/)

**Approach**  -  To add two numbers represented by linked lists 

 (i) Traverse both lists, adding corresponding digits along with any carry.
 <br>
 (ii) Create a new node for each sum, storing the ones place, and carry over the tens place.
 <br>
 (iii) Continue until both lists are exhausted and no carry remains.


 # Linked List In-Place Reversal 

+ ** Reverse Linked List**  [Easy]  (https://leetcode.com/problems/reverse-linked-list/description/)

**Approach**  -  To reverse a linked list 

 (i) Use three pointers: prev, current, and next.
 <br>
 (ii) Traverse the list, setting current.next to prev at each step.
 <br>
 (iii) Move prev and current forward until the end of the list.


+ **Reverse Nodes in K-Group**  [Hard]  (https://leetcode.com/problems/reverse-nodes-in-k-group/description/)

**Approach**  -  To reverse nodes in k-group 

 (i) Use a pointer to check if there are at least k nodes to reverse.
 <br>
 (ii) Reverse the nodes in groups of k using a similar approach to reversing a linked list.
 <br>
(iii) After reversing a group, connect the previous group's tail to the new head.
<br>
 (iv) If fewer than k nodes remain, leave them unchanged.
