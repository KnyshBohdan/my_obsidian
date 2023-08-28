The concept of the inverse of a matrix is a foundational aspect of linear algebra. It refers to a matrix that, when multiplied with the original matrix, results in the identity matrix. Here's a detailed overview:

### Definition

An n×nn×n square matrix A is called invertible (also known as nonsingular or nondegenerate), if there exists a matrix B such that: AB=BA=In where InIn​ denotes the identity matrix. If this is the case, then the matrix B is uniquely determined by A, and is called the (multiplicative) inverse of A, denoted by $A^{−1}$.

### Properties

- **Uniqueness**: The inverse of a matrix, if it exists, is unique.
- **Existence Criteria**: A square matrix is invertible if and only if its determinant is nonzero.
- **Commutative Property**: $(AB)^{−1}=B^{−1}A^{−1}$.
- **Transpose Inverse**: $(A^T)^{−1}=(A^{−1})^{T}$.
- **Determinant of Inverse**: $det⁡A^{−1}=(det⁡A)^{−1}$.

### Methods of Finding the Inverse

1. **Gaussian Elimination**: This method involves creating an augmented matrix with the left side being the matrix to invert and the right side being the identity matrix. Then, Gaussian elimination is used to convert the left side into the identity matrix, causing the right side to become the inverse of the input matrix.
2. **Adjugate Method**: The inverse can be found using the adjugate matrix as follows: A−1=1det⁡(A)adj⁡(A)A−1=det(A)1​adj(A)
3. **Newton's Method**: A generalization of the multiplicative inverse algorithm may be used, particularly when dealing with families of related matrices.

### Examples

- **Invertible Matrix**: B=(−1321−1)B=(−11​23​−1​) is invertible with B−1=(2322)B−1=(22​32​)
- **Non-Invertible Matrix**: A=(2424)A=(22​44​) is non-invertible as its rank is 1.

### Applications

- **Solving Linear Equations**: The inverse is used to solve systems of linear equations.
- **Computer Graphics**: Used in transformations and manipulations of images.
- **Economics**: Utilized in various economic models and optimizations.

### Connections to Other Topics

- **[[Determinants]]**: The existence of an inverse is closely tied to the determinant of a matrix.
- **[[Linear Transformation]]**: Invertible matrices represent bijective linear transformations.
- **[[Matrix Multiplication]]**: The definition of the inverse involves matrix multiplication.
- [[Matrices]]
- [[Linear algebra]]