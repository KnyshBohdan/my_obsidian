Particle Swarm Optimization is inspired by the social behavior of birds and fish. Imagine a swarm of birds searching for food; each bird adjusts its position based on its own experience and the experience of its neighbors. PSO mimics this behavior to find optimal solutions in a multidimensional space.

## Definition

Particle Swarm Optimization is a computational method that optimizes a problem by iteratively improving a population of candidate solutions, known as particles. Each particle's movement is influenced by its local best-known position and is guided toward the best-known positions in the search space.

## Mathematical Formulation

The algorithm maintains a swarm of particles, each with a position xixi​ and a velocity vivi​. The position is updated as follows:

$v_i = w v_i + \phi_p r_p (p_i - x_i) + \phi_g r_g (g - x_i)$

$x_i = x_i + v_i$

Here, w is the inertia weight, ϕp​ and ϕg​ are cognitive and social scaling parameters, and rp​ and rg​ are random vectors.

## Properties and Limitations

- **Global Search**: Capable of exploring large search spaces.
- **Stochastic Nature**: Does not guarantee finding the global optimum.
- **Parameter Sensitivity**: The performance can be sensitive to the choice of parameters like ww, ϕpϕp​, and ϕgϕg​.

## Applications

- **Hybrid Algorithms**: PSO is often hybridized with other algorithms like Bat Algorithm and Differential Evolution to improve performance.
- **Engineering Design**: Used in antenna array optimization and spillway design.
- **Machine Learning**: For feature selection and hyperparameter tuning.

## Connection to Other Topics

- **[[Simulated Annealing]]**: Both are metaheuristic algorithms capable of global search.
- **[[Stochastic Optimization]]**: PSO is a form of stochastic optimization.
- **[[Nonlinear Optimization]]**: Can be applied to nonlinear problems.
- [[Optimization]]