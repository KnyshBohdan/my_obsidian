NP-Completeness is a classification used in computational complexity theory to describe decision problems for which solutions can be verified quickly, but for which no fast method for finding the solutions is known. Essentially, if one NP-complete problem can be solved in polynomial time, then all problems in NP can be as well.

#### Definition

A problem is considered NP-complete if it satisfies the following conditions:

1. It is a decision problem, meaning the output is either "yes" or "no."
2. A "yes" answer can be demonstrated through a polynomial-length solution.
3. The correctness of each solution can be verified in polynomial time.
4. The problem can simulate every other problem in NP, meaning it is NP-hard.

#### Examples

- **Boolean Satisfiability Problem (SAT)**: Determine if a propositional formula can be made true by an appropriate assignment of truth values to its variables.
- **Knapsack Problem**: Given a set of items, each with a weight and a value, determine the maximum value you can accumulate in a knapsack of fixed capacity.
- **Travelling Salesman Problem**: Find the shortest possible route that visits each city exactly once and returns to the original city.

#### Properties

- **Polynomial Time**: Refers to an amount of time considered "quick" for a deterministic algorithm to check a single solution.
- **Nondeterministic Turing Machines**: Used to formalize the idea of a brute-force search algorithm.

#### Applications

- **Heuristic Methods**: Often used to address NP-complete problems in practice.
- **Approximation Algorithms**: Used to find near-optimal solutions when exact solutions are computationally expensive.

#### Connection to Other Topics

- **[[Computational Complexity]]**: NP-Completeness is a subset of computational complexity theory.
- **[[Decision Problems]]**: NP-Complete problems are a specific type of decision problem.
- **[[P vs NP Problem]]**: The question of whether P=NP is one of the most significant open questions in computer science.

 [[Mathematical Logic]]
- [[Automata Theory]]