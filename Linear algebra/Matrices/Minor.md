The concept of a minor in linear algebra is fundamental to understanding various operations on matrices, including determinants, cofactors, and inverses. Here's a detailed explanation:

### Definition

In linear algebra, a minor of a matrix A is the determinant of some smaller square matrix, cut down from A by removing one or more of its rows and columns. Specifically, the minor of the entry in the i-th row and j-th column, denoted Mi,j​, is the determinant of the submatrix formed by deleting the i-th row and j-th column.

### Example

Consider the following 3 by 3 matrix: 
$$\begin{bmatrix} 1 \ 4 \ 7 \\ 3 \ 0 \ 5 \\ -1 \ 9 \ 11\end{bmatrix}$$
To compute the minor M2,3​, we find the determinant of the matrix with row 2 and column 3 removed: 
$$M_{2, 3} = det \begin{bmatrix} 1 \ 4 \\ -1 \ 9 \end{bmatrix} = 9 + 4 = 13$$
### General Definition

A minor of an m×nm×n matrix A of order kk is the determinant of a matrix obtained from A by deleting m−k rows and n−k columns. There are a total of (km​)⋅(kn​) minors of size kk.

### Applications

1. **Cofactor Expansion of the Determinant**: Minors are required for calculating matrix cofactors, which are useful for computing both the determinant and inverse of square matrices.
2. **Inverse of a Matrix**: The matrix formed by all the cofactors of a square matrix is called the cofactor matrix, and its transpose times the reciprocal of the determinant gives the inverse.
3. **Rank Determination**: If a matrix has rank rr, then there exists at least one non-zero minor of order rr, while all larger minors are zero.
4. **Positive Definiteness Test**: For Hermitian matrices, the leading principal minors can be used to test for positive definiteness.

### Connections to Other Topics

- **[[Determinant]]**: Minors are determinants of submatrices, essential in calculating the determinant of a larger matrix.
- **[[Cofactor]]**: A cofactor is obtained by multiplying the minor by (−1)i+j.
- **[[Inverse]]**: Minors are used in calculating the inverse of a matrix using Cramer's rule.
- [[Matrices]]
- [[Linear algebra]]