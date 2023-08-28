In real-world scenarios, many optimization problems are fraught with uncertainties. For instance, if you're optimizing a supply chain, factors like demand, supply, and transportation costs may vary unpredictably. Stochastic Optimization provides the tools to handle such uncertainties effectively.

## Definition

Stochastic Optimization (SO) methods are optimization techniques that incorporate random variables either in the problem formulation itself, which may involve random objective functions or random constraints, or in the optimization algorithm. These methods generalize deterministic optimization methods to handle stochastic problems.

## Mathematical Formulation

While the mathematical formulation can vary depending on the specific problem, the general idea is to optimize an expected value or other statistical properties of the objective function. For example, the goal might be to minimize $E[f(x,ξ)]$, where $f(x,ξ)$ is a random objective function and $E[⋅]$ denotes the expected value.

## Methods and Techniques

- **Stochastic Gradient Descent**: An extension of the gradient descent method that uses a random subset of data in each iteration.
- **Simulated Annealing**: Incorporates randomness to escape local minima.
- **Scenario Optimization**: Uses a set of scenarios to model uncertainty.

## Applications

- **Supply Chain Optimization**: For handling uncertainties in demand, supply, and costs.
- **Machine Learning**: In training models where the data itself could be random.
- **Financial Modeling**: For optimizing portfolios under market uncertainties.

## Connection to Other Topics

- **[[Nonlinear Optimization]]**: Stochastic methods can be applied to nonlinear stochastic problems.
- **[[Convex Optimization]]**: Some stochastic problems may be convex, making them easier to solve.
- **[[Simulation-Based Optimization]]**: Often used in conjunction with stochastic optimization to estimate complex systems.
- [[Optimization]]