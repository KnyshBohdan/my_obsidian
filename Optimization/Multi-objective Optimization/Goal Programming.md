Imagine you're a city planner tasked with optimizing public transportation. You have multiple goals: minimize cost, maximize coverage, and reduce environmental impact. Goal Programming allows you to find solutions that best satisfy these conflicting objectives.

## Definition

Goal Programming is a branch of multi-objective optimization that aims to achieve a set of predefined goals or target values. It measures deviations from these targets both above and below the desired values and minimizes these deviations through an achievement function. This function can be a vector or a weighted sum, depending on the variant of goal programming used.

## Mathematical Formulation

A typical Goal Programming problem can be formulated as:

Minimize Z=∑i=1n(pidi++qidi−)Subject to:fi(x)+di+−di−=bi(i=1,2,…,n)x≥0,di+≥0,di−≥0​Minimize Z=i=1∑n​(pi​di+​+qi​di−​)Subject to:fi​(x)+di+​−di−​=bi​(i=1,2,…,n)x≥0,di+​≥0,di−​≥0​

Here, $d_i^+$​ and $d_i^-$ are the positive and negative deviations from the goal $b_i​$, and $p_i$​ and $q_i$​ are the weights for these deviations.

## Variants

- **Lexicographic Goal Programming**: Used when there's a clear priority ordering among the goals.
- **Weighted Goal Programming**: Used for direct comparisons of objectives, where deviations are multiplied by weights.

## Applications

- **Resource Allocation**: To determine required resources for achieving desired objectives.
- **Decision Making**: Provides the best satisfying solution under varying resources and priorities.

## Connection to Other Topics

- **[[Multi-objective Optimization]]**: Goal Programming is a specific form of multi-objective optimization.
- **[[Linear Optimization]]**: It generalizes the principles of linear programming to handle multiple objectives.
- [[Optimization]]