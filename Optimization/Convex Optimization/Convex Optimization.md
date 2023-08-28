### Definition

Convex optimization is the study of minimizing convex functions over convex sets or, equivalently, maximizing concave functions over convex sets. A function ff is convex if its domain is convex and for all $θ∈[0,1]$ and all x,y in its domain, the following condition holds: 
$$f(\theta x  + (1- \theta) y ) \le \theta f(x) + (1 - \theta)f(y)$$

### Standard Form

A convex optimization problem in standard form is written as:

$$\begin{align} minimize_{x} \ \ \ f(x) \\ subject \ to \ g_{i}(x) \le 0, i = 1, ..., m \\ h_i(x) = 0, \ i = 1, ..., p  \end{align}$$

where:

- $x∈R^n$ is the optimization variable.
- f is the objective function.
- $g_i​$ are convex inequality constraint functions.
- $h_i​$ are affine equality constraint functions.

### Properties

- Every local minimum is a global minimum.
- The optimal set is convex.
- If the objective function is strictly convex, then the problem has at most one optimal point.

### Applications

Convex optimization has applications in various fields:

- **Control Systems**: For automatic control.
- **Finance**: Portfolio optimization and risk analysis.
- **Statistics**: Variations of statistical regression.
- **Engineering**: Circuit design and structural optimization.
- **Data Analysis**: Model fitting and multiclass classification.

### Algorithms

- Bundle methods
- Subgradient projection methods
- **Interior-Point Methods**: Using self-concordant and self-regular barrier functions.
- **Cutting-Plane Methods**: Including ellipsoid and subgradient methods.
- **Dual Subgradients**: And the drift-plus-penalty method.
- Elipsoid method

### Lagrange Multipliers

Consider a convex minimization problem with inequality constraints $g_i(x)≤0$. The Lagrangian function for the problem is: $L(x,λ_0,λ_1,…,λ_m)=λ_0f(x)+λ_1g_1(x)+⋯+λ_mg_m(x)$ where λ0,λ1,…,λm​ are called Lagrange multipliers.

### Software

There is a large software ecosystem for convex optimization, including modeling tools like CVXPY, Convex.jl, and solvers like CVXOPT and MOSEK.

### Connection to Other Topics

- **[[Optimization]]**: Convex optimization is a specialized area within mathematical optimization.
- **[[Linear Optimization]]**: A specific case of convex optimization.
- **[[Machine Learning]]**: Used in hyperparameter tuning and model selection.