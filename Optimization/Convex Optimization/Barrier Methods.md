### Definition

Barrier methods are techniques used to solve convex optimization problems by encoding the feasible set using a barrier function. This approach traverses the interior of the feasible region to find the optimal solution.

### Key Concepts

1. **Barrier Function**: A function that encodes the constraints of the problem, often using a logarithmic barrier.
2. **Barrier Parameter**: A small positive scalar that controls the convergence of the barrier function to the solution.
3. **Perturbed Complementarity**: A condition that ensures the solution lies near the boundary or that the projection of the gradient on the constraint component is almost zero.

### Mathematical Formulation

Consider a nonlinear optimization problem with inequality constraints:

$$\begin{align} minimize_{x} \ \ \ f(x) \\ subject \ to \ x \in R^n \\ c_i(x)\ge 0 \ for \ i = 1, ..., p  \end{align}$$

where $f:R^n→R, c_i:R^n→R$

The associated barrier function is:

$$B(x, \mu) = f(x) - \mu \sum_{i = 1}^m \log(c_i(x))$$

Here, μ is the barrier parameter.

The gradient of the barrier function is:

$$\nabla B(x, \mu) = \nabla f(x) - \mu \sum_{i = 1}^{m} \frac{1}{c_i (x)} \nabla c_i (x)$$

### Algorithms

Barrier methods include:

- **Karmarkar's Algorithm**: A method for linear programming, characterized by polynomial complexity.
- **Primal-Dual Interior-Point Methods**: Including Mehrotra's predictor–corrector algorithm.
- **Chambolle-Pock Algorithm**: Efficiently solves convex optimization problems with non-smooth cost functions.

### Applications

- **Linear Programming**: Finding optimal solutions in polynomial time.
- **Convex Programming**: Generalized to convex programming using self-concordant barrier functions.
- **Image Processing**: Used in imaging applications.

### Advantages and Limitations

- **Advantages**: Barrier methods can be very efficient and are characterized by polynomial complexity.
- **Limitations**: The choice of the barrier parameter and the encoding of the feasible set can be challenging.

### Connection to Other Topics

- **[[Convex Optimization]]**: Barrier methods are a specific technique within convex optimization.
- **[[Linear Programming]]**: Karmarkar's algorithm is a well-known barrier method for linear programming.
- [[Optimization]]