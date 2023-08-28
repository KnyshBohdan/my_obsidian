The concept of a cofactor in linear algebra is closely related to the determinant of a matrix and plays a vital role in various matrix operations. Here's a detailed explanation:

### Definition

In linear algebra, the cofactor of a matrix element is a particular computation involving the determinant of the matrix. For a given element in the i-th row and j-th column of a square matrix A, the cofactor Cij​ is defined as:
$$C_{ij} = (-1)^{i + j} M_{ij}$$
where Mij is the minor of the element, obtained by taking the determinant of the submatrix formed by deleting the i-th row and j-th column.

### Example

Consider the following 3 by 3 matrix: 
$$\begin{bmatrix} 1 \ 4 \ 7 \\ 3 \ 0 \ 5 \\ -1 \ 9 \ 11 \end{bmatrix}$$
⎤​ To compute the cofactor C2,3​, we find the determinant of the matrix with row 2 and column 3 removed: 
$$M_{2, 3} = det \begin{bmatrix} 1 \ 4 \\ -1 \ 9\end{bmatrix} = 9 + 4 = 13$$
So the cofactor of the (2,3) entry is: 
$$C_{2, 3} = (-1)^{2 + 3} M_{2, 3} = -13$$

### Applications

1. **Cofactor Expansion of the Determinant**: The cofactors are used in Laplace's formula for the expansion of determinants, allowing the computation of larger determinants in terms of smaller ones.
2. **Inverse of a Matrix**: The cofactors are essential in computing the inverse of an invertible matrix using Cramer's rule. The matrix formed by all of the cofactors of a square matrix is called the cofactor matrix, and its transpose times the reciprocal of the determinant gives the inverse.

### Connections to Other Topics

- **[[Determinant]]**: Cofactors are derived from the minors of a matrix, which are determinants of submatrices.
- **[[Inverse]]**: Cofactors are used in calculating the inverse of a matrix.
- **[[Laplace Expansion]]**: A method that uses cofactors to calculate determinants.
- [[Linear algebra]]