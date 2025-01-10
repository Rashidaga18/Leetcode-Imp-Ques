# Sorting Important Questions - 

# Bucket Sort Important Questions - 

+ **Top K Frequent Words**  [Medium]  (https://leetcode.com/problems/top-k-frequent-words/description/)

**Approach**  -  To find the top K frequent words 

 (i) Use a hash map to store the frequency of each word.
 <br>
 (ii) Use a min heap to keep track of the top K most frequent words.
 <br>
 (iii) If the heap size exceeds K, remove the word with the smallest frequency.
 <br>
 (iv) Sort the heap by frequency and lexicographical order if frequencies are equal.

# Merge Sort Important Questions - 

+ **Sort List**  [Medium]  (https://leetcode.com/problems/sort-list/description/)

**Approach**  -  To sort a linked list 

 (i) Use Merge Sort for optimal performance.
 <br>
 (ii) Recursively divide the list into two halves until each sublist contains one node.
 <br>
 (iii) Merge the sorted halves back together, ensuring the list remains sorted.


# Quick Sort Important Questions - 

+ **Sort Colors**  [Medium]  (https://leetcode.com/problems/sort-colors/description/)

**Approach**  -  To sort colors (0s, 1s, 2s) 

 (i) Use the Dutch National Flag Algorithm with three pointers
 <br>
 (ii) low for 0s, mid for 1s, and high for 2s.
 <br>
 (iii) Traverse the array
 <br>
 (iv) Swap and move low for 0s.
 <br>
 (v) Move mid for 1s.
 <br>
 (vi) Swap and move high for 2s.


+ **K-th Largest Element in an Array**  [Medium]  (https://leetcode.com/problems/kth-largest-element-in-an-array/description/)

**Approach**  -  To find the k-th largest element 

  (i) Use a min-heap of size k.
  <br>
  (ii) Traverse the array, adding elements to the heap.
  <br>
  (iii) If the heap size exceeds k, remove the smallest element.
  <br>
  (iv) The root of the heap is the k-th largest element.
