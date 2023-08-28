Imagine you've built a model to optimize the routing of delivery trucks. Sensitivity Analysis is the tool you'd use to understand how changes in fuel prices, traffic conditions, or delivery times would affect your optimal route. It's like a "what-if" analysis for your optimization problem.

## Definition

Sensitivity Analysis is the study of how the uncertainty in the output of a mathematical model or system can be allocated to different sources of uncertainty in its inputs. It involves recalculating outcomes under alternative assumptions to determine the impact of a variable. This analysis is useful for testing the robustness of the results of a model or system in the presence of uncertainty.

## Mathematical Formulation

In the context of optimization, Sensitivity Analysis often involves examining how changes in the coefficients of the objective function or constraints affect the optimal solution. Mathematically, if the optimization problem is:

$$\begin{align} Minimize \ f(x) \\ Subject \ to \ g_i (x) \le 0 \ \ (i = 1, 2, ..., m) \end{align}$$

Sensitivity Analysis would investigate how changes in f(x) or gi(x) affect the optimal solution x∗.

## Properties

- **Robustness Testing**: Evaluates the stability of an optimization solution against changes in parameters.
- **Uncertainty Reduction**: Identifies model input that causes significant uncertainty in the output.

## Applications

- **Resource Allocation**: To understand how changes in resource availability affect optimization solutions.
- **Reliability Engineering**: To assess the effects of changes in data values, detect outliers, and optimize resources.
- **Decision Making**: Enhances communication from modelers to decision makers by making recommendations more credible.

## Connection to Other Topics

- **[[Optimization]]**: Sensitivity Analysis is an integral part of any optimization problem to ensure robust solutions.
- **[[Duality Theory]]**: Sensitivity Analysis can be used in tandem with Duality Theory to understand the robustness of both primal and dual solutions.
- [[Linear Optimization]]
- [[Optimization]]