Singular Value Decomposition (SVD) is a method of factorizing a real or complex matrix. It generalizes the eigendecomposition of a square normal matrix with an orthonormal eigenbasis to any m×nm×n matrix. SVD is related to the polar decomposition and has broad applications in mathematics, engineering, and statistics.

### Definition

Given a complex matrix MM, the SVD is a factorization of the form: M=UΣV∗M=UΣV∗ where:

- UU is an m×mm×m unitary matrix.
- ΣΣ is a rectangular diagonal matrix with non-negative real numbers on the diagonal.
- VV is an n×nn×n complex unitary matrix, and V∗V∗ is the conjugate transpose of VV.

If MM is real, then UU and VV can be guaranteed to be real orthogonal matrices, and the SVD is often denoted as UΣVTUΣVT.

### Singular Values and Vectors

The diagonal entries of ΣΣ are known as the singular values. The number of non-zero singular values is equal to the rank of the matrix. The columns of UU and VV are called left-singular vectors and right-singular vectors of MM, respectively. They form two sets of orthonormal bases.

### Geometric Interpretation

The SVD can be visualized as three simple transformations:

1. **Rotation**: Represented by VV, it rotates the space.
2. **Scaling**: Represented by ΣΣ, it scales the coordinates along the axes.
3. **Rotation**: Represented by UU, it performs another rotation.

The singular values can be interpreted as the magnitude of the semiaxes of an ellipse in 2D or an ellipsoid in higher dimensions.

### Example

Consider the 4×54×5 matrix: M=[10002003000000002000]M=⎣

⎡​1000​0002​0300​0000​2000​⎦

⎤​ A singular value decomposition of this matrix is given by matrices UU, ΣΣ, and V∗V∗, with the scaling matrix ΣΣ having non-negative real numbers on the diagonal.

### Applications

- **Pseudoinverse**: Computing the pseudoinverse of a matrix.
- **Matrix Approximation**: Approximating a matrix using a reduced number of singular values.
- **Determining Rank**: Finding the rank, range, and null space of a matrix.
- **Signal Processing**: Applications in signal processing, least squares fitting of data, and process control.

### Connections

- [[Matrix Decomposition]]: SVD is a specific type of matrix decomposition.
- [[Eigenvalues and Eigenvectors]]: SVD generalizes the eigendecomposition of a square normal matrix.
- [[Rank]]: The number of non-zero singular values is equal to the rank of the matrix.
- [[Linear algebra]]
- [[Matrices]]