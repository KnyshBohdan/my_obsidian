Genetic Algorithms are a fascinating blend of biology and computer science, mimicking the process of natural selection to evolve a population of candidate solutions towards an optimal solution.

## Definition

A Genetic Algorithm is a metaheuristic that simulates the process of natural selection to generate high-quality solutions for optimization and search problems. It operates on a population of potential solutions using the principles of selection, crossover (recombination), and mutation.

## Mathematical Formulation

In GAs, each candidate solution is represented as a string of bits, characters, or any other data structure. The fitness of each individual is evaluated using a fitness function. The algorithm then selects individuals based on their fitness and applies crossover and mutation operations to create a new generation.

New Generation=Crossover(Selection(Population))+Mutation

## Properties and Limitations

- **Global Search**: Capable of exploring a large solution space.
- **Stochastic Nature**: Results may vary between runs.
- **Computational Complexity**: May require a large number of generations for convergence.

## Applications

- **Optimizing Decision Trees**: For better performance in machine learning.
- **Solving Sudoku Puzzles**: As a search problem.
- **Hyperparameter Optimization**: In machine learning models.

## Connection to Other Topics

- **[[Particle Swarm Optimization]]**: Both are population-based optimization algorithms.
- **[[Simulated Annealing]]**: GAs can be considered an alternative to simulated annealing for global optimization.
- **[[Stochastic Optimization]]**: Genetic Algorithms are a form of stochastic optimization.
- [[Optimization]]