The determinant is a fundamental concept in linear algebra, associated with square matrices. It provides valuable insights into the properties of the matrix and the linear transformation it represents. Here's an in-depth look at the determinant:

### Definition

The determinant is a scalar value that is a function of the entries of a square matrix. It characterizes properties of the matrix and the linear map represented by the matrix. The determinant of a matrix AA is denoted as det⁡(A)det(A), det⁡det, or ∣A∣∣A∣.

### Properties

1. **Nonzero Determinant**: The determinant is nonzero if and only if the matrix is invertible, and the linear map represented by the matrix is an isomorphism.
2. **Product of Matrices**: The determinant of a product of matrices is the product of their determinants.
3. **Identity Matrix**: The determinant of the identity matrix is 1.
4. **Row Operations**: Exchange of two rows (or columns) multiplies the determinant by −1. Multiplying a row (or column) by a number multiplies the determinant by that number. Adding to a row (or column) a multiple of another row (or column) does not change the determinant.

### Geometric Meaning

The determinant represents the signed n-dimensional volume of a parallelepiped. In 2D, the absolute value of the determinant of a matrix gives the area of the parallelogram formed by the vectors representing the sides. The sign indicates the orientation.

### Calculating Determinants

- **2 × 2 Matrix**: For a matrix ∣abcd∣∣

∣​ac​bd​∣- ∣​, the determinant is ad−bcad−bc.
- **3 × 3 Matrix**: For a matrix ∣abcdefghi∣∣
∣​adg​beh​cfi​∣- ∣​, the determinant is aei+bfg+cdh−ceg−bdi−afhaei+bfg+cdh−ceg−bdi−afh.
- **Leibniz Formula**: For an n × n matrix, the determinant can be expressed as a sum of signed products of matrix entries using permutations and their signatures.
- **Laplace Expansion**: Expresses the determinant as a linear combination of determinants of (n-1) × (n-1) submatrices.
- **Gaussian Elimination**: Expresses the determinant as the product of the diagonal entries of a diagonal matrix obtained by elementary row operations.

### Applications

- **Solving Linear Equations**: Determinants can be used to solve systems of linear equations (Cramer's rule).
- **Eigenvalues**: Used for defining the characteristic polynomial of a matrix, whose roots are the eigenvalues.
- **Geometry and Calculus**: Used in geometry for expressing volumes and in calculus for changes of variables in multiple integrals.

### Connections to Other Topics

- **[[Matrices]]**: Determinants are defined for square matrices.
- **[[Inverse]]**: A matrix is invertible if its determinant is nonzero.
- **[[Eigenvalues and Eigenvectors]]**: Determinants are used in finding eigenvalues.
- **[[Laplace Expansion]]**: A method to calculate determinants.
- [[Linear algebra]]