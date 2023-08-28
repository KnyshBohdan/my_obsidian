The rank of a matrix is a fundamental concept in linear algebra that provides insight into the structure and properties of the matrix. Here's a detailed explanation:

### Definition

The rank of a matrix A is the dimension of the vector space generated (or spanned) by its columns. This corresponds to the maximal number of linearly independent columns of A. Equivalently, it is identical to the dimension of the vector space spanned by its rows. The rank is commonly denoted by rank(A) or rk(A).

### Main Definitions

1. **Column Rank**: The column rank of a matrix is the dimension of the column space, representing the maximal number of linearly independent columns.
2. **Row Rank**: The row rank is the dimension of the row space, representing the maximal number of linearly independent rows.
3. **Full Rank**: A matrix is said to have full rank if its rank equals the largest possible for a matrix of the same dimensions, which is the lesser of the number of rows and columns.
4. **Rank-Deficient**: A matrix is said to be rank-deficient if it does not have full rank.

### Example

The matrix 
$$\begin{bmatrix} 1 \ 0 \ 1 \\ -2 \ -3 \ 1 \\ 3 \ 3 \ 0 \end{bmatrix}$$
has rank 2: the first two columns are linearly independent, so the rank is at least 2, but since the third is a linear combination of the first two, the three columns are linearly dependent, so the rank must be less than 3.

### Computing the Rank

The rank of a matrix can be computed using various methods:

- **Gaussian Elimination**: By reducing the matrix to row echelon form, the rank equals the number of non-zero rows.
- **Singular Value Decomposition (SVD)**: The rank equals the number of non-zero singular values.
- **Determinantal Rank**: The rank is the size of the largest non-vanishing minor in the matrix.

### Applications

- **System of Linear Equations**: The rank of a matrix is related to the solvability of the corresponding system of linear equations.
- **Linear Transformation**: The rank of a linear map is defined as the dimension of its image.
- **Rank-Nullity Theorem**: The rank of a matrix plus the dimension of its kernel (nullity) equals the number of columns.

### Connections to Other Topics

- **[[Minor]]**: The rank can be determined by the size of the largest non-vanishing minor.
- **[[Linear Independence]]**: The rank represents the maximal number of linearly independent columns or rows.
- **[[Matrices]]**: The rank is one of the most fundamental characteristics of a matrix.
- [[Linear algebra]]