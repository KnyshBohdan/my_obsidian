Matrices are fundamental objects in linear algebra, representing a rectangular array of numbers, symbols, or expressions arranged in rows and columns. Here's a comprehensive overview of matrices:

### Definition

A matrix (plural matrices) is a rectangular array of numbers, symbols, or expressions, arranged in rows and columns. The size of a matrix is defined by the number of rows and columns it contains, denoted as an m×n matrix. For example, the matrix $\begin{bmatrix} 1 \ 2 \ 3 \\ 1 \ 2 \ 3 \end{bmatrix}$ is a 2×3 matrix.

### Types of Matrices

- **Row Vector**: A matrix with one row.
- **Column Vector**: A matrix with one column.
- **Square Matrix**: A matrix with the same number of rows and columns.
- **Infinite Matrix**: A matrix with an infinite number of rows or columns.
- **Empty Matrix**: A matrix with no rows or no columns.

### Basic Operations

1. **Addition**: The sum of two matrices is calculated entrywise. $\begin{bmatrix} 1 \ 3 \ 1 \\ 1 \ 0 \ 0 \end{bmatrix}$ +$\begin{bmatrix} 0 \ 0 \ 5 \\ 7 \ 5 \ 0 \end{bmatrix}$ =$\begin{bmatrix} 1 \ 3 \ 6 \\ 8 \ 5 \ 0 \end{bmatrix}$
2. **Scalar Multiplication**: Multiplying every entry of a matrix by a number (scalar). 2⋅[18−34−25]=[216−68−410]2⋅[14​8−2​−35​]=[28​16−4​−610​]
3. **Transposition**: Turning rows into columns and vice versa. $$\begin{bmatrix} 1 \ 2 \ 3 \\ 0 \ -6\ 7 \end{bmatrix}^T = \begin{bmatrix} 1 \ 0 \\  2 \ -6 \\ 3 \ 7 \end{bmatrix} $$
2. **Matrix Multiplication**: Defined if the number of columns of the left matrix is the same as the number of rows of the right matrix.

### Applications

- **Linear Maps**: Matrices represent linear maps and allow explicit computations in linear algebra.
- **Geometry**: Used for specifying and representing geometric transformations such as rotations.
- **Numerical Analysis**: Many computational problems are solved by reducing them to matrix computations.
- **Graph Theory**: Incidence matrices and adjacency matrices are used in graph theory.

### Connections to Other Topics

- **[[Linear Independence]]**: Matrices are used to represent systems of linear equations.
- **[[Linear Transformation]]**: Square matrices are used to represent linear transformations from a vector space to itself.
- **[[Determinant]]**: A special number associated with square matrices, fundamental for studying properties like invertibility.
- **[[Eigenvalues and Eigenvectors]]**: Related to square matrices and essential in various applications.
- [[Linear algebra]]