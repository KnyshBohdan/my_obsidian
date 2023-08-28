Suppose you're a project manager tasked with optimizing both the cost and the quality of a product. The Weighted Sum Method allows you to balance these conflicting objectives by assigning weights to each, thereby converting the multi-objective problem into a single-objective one.

## Definition

The Weighted Sum Method scalarizes a set of multiple objectives into a single composite objective function. This is achieved by multiplying each individual objective function by a user-defined weight and summing them up. The method is particularly effective when dealing with convex problems but has limitations in non-convex spaces.

## Mathematical Formulation

The general mathematical formulation is:

$$F(x) = w_1 f_1 (x) + w_2 f_2(x) + ... + w_M f_M (x)$$

Here, F(x) is the composite objective function, $f_i(x)$ are the individual objective functions, and wiwi​ are the weights assigned to each objective.

## Steps for Implementation

1. **Normalize Objectives**: Minimize or maximize each objective subject to all constraints.
2. **Assign Weights**: Define weights $w_1,w_2,…,w_M​$ based on the relative importance of each objective.
3. **Formulate Composite Objective**: Combine the weighted objectives into a single composite objective function.
4. **Optimize**: Solve the single-objective optimization problem to find the optimal solution.

## Applications

- **Chemical Processes**: For optimizing reaction yields and minimizing waste.
- **Investment Strategies**: For balancing risk and return.
- **Virtual Network Allocation**: For optimizing resource allocation in cloud computing.

## Connection to Other Topics

- **[[Multi-objective Optimization]]**: The Weighted Sum Method is a specific technique within multi-objective optimization.
- **[[Pareto Efficiency]]**: The method aims to find solutions close to the Pareto-optimal front.
- **[[Decision Theory]]**: Used in multi-criteria decision analysis for evaluating alternatives.
- [[Optimization]]