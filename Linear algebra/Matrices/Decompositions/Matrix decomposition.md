Matrix decomposition, also known as matrix factorization, is a fundamental concept in linear algebra that involves representing a given matrix as a product of other matrices. This concept has various applications in numerical analysis, scientific computing, and engineering. Here's an overview of some of the key matrix decompositions:

### 1. LU Decomposition

- **Definition**: Decomposes a matrix AA into a product of a lower triangular matrix LL and an upper triangular matrix UU, i.e., A=LU.
- **Applications**: Used to solve systems of linear equations and invert matrices.
- **Related**: LDU decomposition, LUP decomposition with permutation matrix.

### 2. QR Decomposition

- **Definition**: Decomposes a matrix AA into a product of an orthogonal matrix QQ and an upper triangular matrix RR, i.e., A=QRA=QR.
- **Applications**: Used in solving linear least squares problems and eigenvalue problems.

### 3. Cholesky Decomposition

- **Definition**: Decomposes a Hermitian, positive-definite matrix into the product of a lower triangular matrix and its conjugate transpose, i.e., A=LL∗A=LL∗.
- **Applications**: Used in optimization, solving linear equations, and statistical computations.

### 4. Eigendecomposition

- **Definition**: Decomposes a matrix AA into a product of a matrix of its eigenvectors VV and a diagonal matrix DD containing its eigenvalues, i.e., A=VDV−1A=VDV−1.
- **Applications**: Used in differential equations, stability analysis, and diagonalization of matrices.

### 5. Singular Value Decomposition (SVD)

- **Definition**: Decomposes a matrix AA into a product of three matrices U,D,V∗U,D,V∗, where UU and VV are unitary, and DD is a nonnegative diagonal matrix.
- **Applications**: Used in signal processing, data compression, and numerical analysis.

### 6. Jordan Decomposition

- **Definition**: Includes the Jordan normal form and the Jordan–Chevalley decomposition.
- **Applications**: Generalizes eigendecomposition to cases with repeated eigenvalues.

### 7. Schur Decomposition

- **Definition**: Decomposes a matrix into a unitary matrix and an upper triangular matrix.
- **Applications**: Used in numerical stability and similarity transformations.

### 8. QZ Decomposition

- **Definition**: Generalized Schur decomposition for square matrices.
- **Applications**: Used in solving generalized eigenvalue problems.

### 9. Polar Decomposition

- **Definition**: Decomposes any square complex matrix into a product of a unitary matrix and a positive semidefinite Hermitian matrix.
- **Applications**: Related to the singular value decomposition and has applications in quantum mechanics.

### 10. Hessenberg Decomposition

- **Definition**: Decomposes a matrix into a unitary matrix and a Hessenberg matrix.
- **Applications**: Often the first step in the Schur decomposition.

### 11. Other Decompositions

- **Takagi's Factorization**: For square, complex, symmetric matrices.
- **Complete Orthogonal Decomposition**: Similar to SVD.
- **Scale-Invariant Decompositions**: Variants of existing decompositions that are invariant with respect to diagonal scaling.

## Connections

* [[Linear algebra]]
* [[Matrices]]