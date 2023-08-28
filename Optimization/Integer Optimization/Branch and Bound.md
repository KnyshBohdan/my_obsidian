## Definition

Branch and Bound (BB, B&B, or BnB) is an algorithmic paradigm designed for solving optimization problems. It decomposes the problem into smaller sub-problems and employs a bounding function to eliminate those sub-problems that cannot contain the optimal solution. The algorithm operates in a state space search framework, where the set of candidate solutions forms a rooted tree. Each branch of this tree represents a subset of the solution set. The algorithm evaluates each branch against upper and lower estimated bounds on the optimal solution and discards it if it cannot yield a better solution than the best one found so far.

## Mathematical Formulation

The algorithm aims to find a value xx that maximizes or minimizes an objective function f(x) over a feasible region S. The algorithm operates on two principles:

1. **Branching**: It recursively splits the search space S into smaller spaces Si​.
2. **Bounding**: It uses bounds to prune the search space, eliminating candidate solutions that cannot contain an optimal solution.

## Examples

1. **Traveling Salesman Problem**: Branch and Bound is often used to find the shortest possible route that visits each city exactly once and returns to the original city.
2. **Integer Linear Programming**: It is used to find the best integer solutions to linear programming problems.

## Properties

- **Efficient Estimation**: The algorithm's efficiency depends on the accurate estimation of lower and upper bounds.
- **Degeneracy**: If no bounds are available, the algorithm degenerates into an exhaustive search.

## Applications

- **Operations Research**: Used in solving complex scheduling, routing, and network design problems.
- **Computer Science**: Employed in search algorithms and decision tree constructions.
- **Data Science**: Used in feature selection and optimization problems.

## Connection to Other Topics

- **[[Optimization]]**: Branch and Bound is a specific type of optimization algorithm.
- **[[Combinatorial Optimization]]**: It is particularly useful for solving discrete and combinatorial optimization problems.
- **[[Dynamic Programming]]**: While dynamic programming is used for optimization, Branch and Bound is often more efficient for problems with a large state space.
- **[[Heuristic Methods]]**: Heuristic methods like Greedy and Genetic Algorithms can sometimes be used in conjunction with Branch and Bound to improve efficiency.
- [[Integer Optimization]]