The Gram–Schmidt process is a fundamental method in linear algebra for orthonormalizing a set of vectors in an inner product space, most commonly the Euclidean space equipped with the standard inner product. Here's a detailed exploration of the Gram–Schmidt process:

### Introduction

The Gram–Schmidt process takes a finite, linearly independent set of vectors S={v1,…,vk} and generates an orthogonal set S′ that spans the same nn-dimensional subspace. It's a crucial step in various mathematical and computational procedures, such as QR decomposition.

### Definition and Procedure

The Gram–Schmidt process works by defining the projection operator: 
$$proj_u(v) = \frac{⟨v,u⟩}{⟨u,u⟩}u$$
where ⟨v,u⟩ denotes the inner product of the vectors.

The process then proceeds as follows:

1. $u_1=v_1,e_1=\frac{u_1}{∥u_1∥}$
2. $u_2=v_2−proj⁡_{u_1}(v_2),e_2=\frac{u_2}{∥u_2∥}​​$
3. $u_3=v_3−proj⁡_{u_1}(v_3)−proj⁡_{u_2}(v3),e_3=\frac{u_3}{∥u_3∥}$
4. Continue this pattern for all vectors in the set.

The sequence e1,e2,…,ek​ is the required system of orthonormal vectors.

### Example

Consider the set of vectors $S=\{\begin{bmatrix} 3 \\ 1 \end{bmatrix},\begin{bmatrix}2 \\ 2 \end{bmatrix}\}$ Applying the Gram–Schmidt process, we obtain:

- $u_1=\begin{bmatrix} 3 \\ 1 \end{bmatrix}$
- $u_2=\begin{bmatrix} 2 \\ 2 \end{bmatrix}−\frac{8}{10} \begin{bmatrix} 3 \\ 1 \end{bmatrix} = \begin{bmatrix} -2/5 \\ 6/5 \end{bmatrix}$

### Numerical Stability

The classical Gram–Schmidt process can suffer from numerical instability due to rounding errors. A modification known as the "modified Gram-Schmidt" (MGS) process introduces smaller errors in finite-precision arithmetic and is often preferred in numerical applications.

### Connections to Other Topics

- **[[Linear Independence]]**: The Gram–Schmidt process requires a linearly independent set of vectors as input.
- **[[Inner Product Spaces]]**: The process operates within the context of inner product spaces.
- **[[Orthogonality]]**: The result of the process is a set of orthogonal (or orthonormal) vectors.
- [[Linear algebra]]