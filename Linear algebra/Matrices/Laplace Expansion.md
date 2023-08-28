The Laplace expansion, also known as cofactor expansion, is a method used in linear algebra to express the determinant of a square matrix. It's named after Pierre-Simon Laplace and is a fundamental concept in the study of matrices.

### Definition and Formula

The Laplace expansion expresses the determinant of an n×nn×n matrix B as a weighted sum of minors, which are the determinants of some (n−1)×(n−1) submatrices of B. Specifically, the formula is given by: 
$$det(B) = \sum_{j = 1}^{n} (-1)^{i + j}b_{i, j} m_{i, j}$$
where bi,j​ is the entry of the i-th row and j-th column of B, and mi,j is the determinant of the submatrix obtained by removing the ii-th row and the jj-th column. The term (−1)i+jmi,j​ is called the cofactor of Bi,j

### Example

Consider the matrix: 
$$B = \begin{bmatrix} 1 \ 2 \ 3 \\ 4 \ 5\ 6 \\ 7 \ 8 \ 9 \end{bmatrix}$$
​ The determinant of this matrix can be computed using the Laplace expansion along any row or column. An expansion along the first row yields: 
$$|B| = 1 \begin{bmatrix} 5 \ 6 \\ 8 \ 9\end{bmatrix} - 2 \begin{bmatrix} 4 \ 6 \\ 7 \ 9 \end{bmatrix} + 3 \begin{bmatrix} 4 \ 5 \\ 7\ 8 \end{bmatrix} = 0$$
### Applications

- **Proofs**: Useful in proofs, allowing recursion on the size of matrices.
- **Computations**: One of several ways to view and compute the determinant, although it becomes inefficient for large matrices.

### Connections to Other Topics

- **[[Determinant]]**: Laplace expansion is a method to compute determinants.
- **[[Matrices]]**: The concept is directly related to the study of matrices and their properties.
- [[Linear algebra]]

### Computational Expense

The Laplace expansion is computationally inefficient for high-dimension matrices, with a time complexity of O(n!). For practical computations, methods like LU decomposition are often preferred, as they yield determinants with a time complexity of O(n3).