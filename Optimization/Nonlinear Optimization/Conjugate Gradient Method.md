The Conjugate Gradient Method is an elegant compromise between the Newton's method and the method of steepest descent, offering a balance between computational efficiency and rate of convergence.

## Definition

The Conjugate Gradient Method is designed to minimize a quadratic function $F(x) = \frac{1}{2} x^T A x - bx$, where A is a symmetric positive-definite matrix and x and b are vectors. The method is often implemented as an iterative algorithm.

## Mathematical Formulation

The core idea is to choose orthogonal search directions and take exactly one step in each direction. The algorithm iteratively updates x as:

$$x_{n + 1} = x_n + \alpha_n d_n$$

Here, αn​ is the step size and dn​ is the search direction that is A-conjugate to the previous directions.

## Properties and Limitations

- **Convergence**: Theoretically, the method converges in at most nn steps, where nn is the size of the matrix AA.
- **Computational Efficiency**: Avoids the high computational cost of Newton's method.
- **Applicability**: Particularly useful for large and sparse systems.

## Applications

- **Iterative Image Reconstruction**: In medical imaging and astronomy.
- **Facial Recognition**: In computer vision.
- **Deep Learning**: For training neural networks.

## Connection to Other Topics

- **[[Newton's Method]]**: CGM is a compromise between Newton's method and steepest descent.
- **[[Linear Optimization]]**: CGM is often used in linear optimization problems.
- **[[Nonlinear Optimization]]**: Can be generalized for nonlinear optimization.
- [[Optimization]]