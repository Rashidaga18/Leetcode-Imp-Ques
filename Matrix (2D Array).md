# Matrix (2D Array) Important Questions -

+ **Spiral Matrix**  [Medium]  (https://leetcode.com/problems/spiral-matrix/description/)

**Approach**  -  Use a layer-by-layer traversal approach:

  (i) Initialize four boundaries: top, bottom, left, and right.
  <br>
  (ii) Traverse from left to right across the top, top to bottom down the right, right to left across the bottom, and bottom to top up the left.
  <br>
  (iii) Adjust the boundaries inward after each traversal until all elements are visited.

+ **Rotate Image**  [Medium]  (https://leetcode.com/problems/rotate-image/description/)

**Approach**  -  To rotate the image 90 degrees clockwise

  (i) Transpose the matrix: Swap elements across the diagonal (matrix[i][j] with matrix[j][i]).
  <br>
  (ii) Reverse each row of the transposed matrix.

+ **Set Matrix Zeroes**  [Medium]  (https://leetcode.com/problems/set-matrix-zeroes/description/)

**Approach**  -  To set matrix zeroes 

  (i) Mark rows and columns that need to be set to zero using the first row and first column as markers.
  <br>
  (ii) Traverse the matrix, and for any zero, mark the corresponding row and column in the first row and column.
  <br>
  (iii) After marking, set the matrix elements to zero, except for the first row and first column.
  <br>
  (iv) Finally, set the first row and first column to zero if needed.
