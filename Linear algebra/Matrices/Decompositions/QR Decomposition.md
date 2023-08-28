QR Decomposition is a method used to decompose a matrix into two matrices: an orthonormal matrix QQ and an upper triangular matrix RR. It plays a vital role in solving linear least squares problems and is the basis for certain eigenvalue algorithms, such as the QR algorithm.

### Definition

Given a matrix AA, the QR Decomposition represents it as a product of two matrices: A=QRA=QR where:

- QQ is an orthonormal matrix (its columns are orthogonal unit vectors, and QT=Q−1QT=Q−1).
- RR is an upper triangular matrix (also called a right triangular matrix).

### Cases and Definitions

1. **Square Matrix**: Any real square matrix can be decomposed into QQ and RR, where QQ is an orthogonal matrix, and RR is an upper triangular matrix. If the matrix is invertible, the factorization is unique if the diagonal elements of RR are positive.
2. **Rectangular Matrix**: For a complex m×nm×n matrix, with m≥nm≥n, it can be factored as the product of an m×mm×m orthogonal matrix QQ and an m×nm×n upper triangular matrix RR.

### Computing the QR Decomposition

Several methods can be used to compute the QR Decomposition, including:

- **Gram–Schmidt Process**: This method is simple but can be numerically unstable.
- **Householder Transformations**: This method uses reflections to calculate the factorization and offers greater numerical stability.
- **Givens Rotations**: Another method to compute the decomposition.

### Example

Consider the decomposition of the matrix: A=[12−5146167−68−424−41]A=⎣

⎡​126−4​−5116724​4−68−41​⎦⎤​ Using the Gram–Schmidt process, the decomposition can be calculated as: Q=[6/7−69/175−58/1753/7158/1756/175−2/76/35−33/35]Q=⎣⎡​6/73/7−2/7​−69/175158/1756/35​−58/1756/175−33/35​⎦⎤​ R=[1421−140175−700035]R=⎣⎡​1400​211750​−14−7035​⎦

⎤​

### Applications

- **Solving Linear Equations**: QR Decomposition is used to solve linear equations and linear least squares problems.
- **Eigenvalue Algorithms**: It forms the basis for the QR algorithm, used to find the eigenvalues of a matrix.

### Connections

- [[Matrix Decomposition]]: QR Decomposition is a specific type of matrix decomposition.
- [[Orthogonality]]: The QQ matrix in QR Decomposition is an orthogonal matrix.
- [[Eigenvalues and Eigenvectors]]: QR Decomposition is used in algorithms to find eigenvalues and eigenvectors.
- [[Gram-Shmidt Process]]: A method used to compute the QR Decomposition.
- [[Linear algebra]]
* [[Matrices]]
### Conclusion