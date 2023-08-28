Imagine you're an operations researcher trying to optimize a complex supply chain network. Traditional optimization methods might get stuck in local optima, but Simulated Annealing can help you find a near-global optimum.

## Definition

Simulated Annealing is a probabilistic technique for approximating the global optimum of a given function. It is inspired by the annealing process in metallurgy, where a material is heated and then slowly cooled to remove defects and find a low-energy state.

## Mathematical Formulation

The algorithm starts with an initial solution and iteratively moves to a new solution in the neighborhood of the current one. The acceptance of the new solution is based on a probability function that depends on the difference in objective function values and a parameter known as "temperature," which decreases over time.

$$P(\Delta E, T) = e ^{- \frac{\Delta E}{T}}$$

Here, ΔE is the change in the objective function, and T is the temperature.

## Properties and Limitations

- **Global Search**: Capable of escaping local minima to explore the global solution space.
- **Cooling Schedule**: The rate at which the temperature decreases is crucial for the algorithm's performance.
- **Stochastic Nature**: The algorithm is probabilistic, so it may not find the exact global optimum.

## Applications

- **Combinatorial Optimization**: Such as the traveling salesman problem and job-shop scheduling.
- **Machine Learning**: For feature selection and hyperparameter tuning.
- **Real-world Problems**: Like large-scale aircraft trajectory planning.

## Connection to Other Topics

- **[[Stochastic Optimization]]**: Simulated Annealing is a form of stochastic optimization.
- **[[Nonlinear Optimization]]**: Can be applied to nonlinear problems.
- **[[Metaheuristic Algorithms]]**: SA is one of the well-known metaheuristic methods.
- [[Optimization]]