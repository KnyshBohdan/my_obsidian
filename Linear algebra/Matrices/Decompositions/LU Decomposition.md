#### Definition

LU Decomposition, or Lower-Upper Decomposition, is a method in numerical analysis and linear algebra that factors a matrix into the product of a lower triangular matrix LL and an upper triangular matrix UU. The decomposition can be represented as: A=LUA=LU where all elements above the diagonal in LL are zero, and all elements below the diagonal in UU are zero.

#### Example

For a 3 × 3 matrix: A=[a11a12a13a21a22a23a31a32a33]A=⎣

⎡​a11​a21​a31​​a12​a22​a32​​a13​a23​a33​​⎦⎤​ its LU decomposition looks like this: A=[ℓ1100ℓ21ℓ220ℓ31ℓ32ℓ33][u11u12u130u22u2300u33]A=⎣⎡​ℓ11​ℓ21​ℓ31​​0ℓ22​ℓ32​​00ℓ33​​⎦⎤​⎣⎡​u11​00​u12​u22​0​u13​u23​u33​​⎦

⎤​

#### Key Concepts

- **Lower Triangular Matrix**: A matrix where all the entries above the main diagonal are zero.
- **Upper Triangular Matrix**: A matrix where all the entries below the main diagonal are zero.
- **Permutation Matrix**: Sometimes, a permutation matrix is included in the product, especially when pivoting is required.

#### Applications

- **Solving Linear Equations**: LU decomposition is commonly used to solve square systems of linear equations.
- **Matrix Inversion**: It is a key step when inverting a matrix.
- **Computing Determinants**: LU decomposition aids in computing the determinant of a matrix.

#### Algorithm

1. **Check for Proper Ordering**: Ensure that the matrix can be factorized into LL and UU.
2. **Decompose**: Decompose the matrix into a lower triangular matrix LL and an upper triangular matrix UU.
3. **Handle Pivoting**: If necessary, include a permutation matrix to handle pivoting.

#### Connections to Other Topics

- **[[Matrix Decomposition]]**: LU Decomposition is a specific type of matrix factorization method.
- **[[Gaussian Elimination]]**: LU Decomposition can be viewed as the matrix form of Gaussian elimination.
- **[[Determinant]]**: The determinant can be computed using LU Decomposition.
- **[[Cholesky Decomposition]]**: A specialized case for symmetric positive-definite matrices.
- [[Linear algebra]]
- [[Matrices]]