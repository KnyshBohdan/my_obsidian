
### Definition

The KKT conditions are applied to the following nonlinear optimization problem in standard form:

- **Minimize**: f(x)f(x)
- **Subject to**:
    - Inequality constraints: $gi(x)≤0, i=1,…,m$
    - Equality constraints: $hj(x)=0, j=1,…,ℓ$

The corresponding Lagrangian function is given by: $L(x,μ,λ)=f(x)+μ⊤g(x)+λ⊤h(x)$

### Karush–Kuhn–Tucker Conditions

The KKT conditions consist of the following four groups of conditions:

1. **Stationarity**: The gradient of the Lagrangian with respect to the optimization variables must be zero: 
$$\partial f(x^{*}) + \sum_{j = 1}^l \lambda_{j} \partial h_{j}(x^*) + \sum_{i = 1}^{m} \mu_{i} \partial g_i(x^*) \in O$$
    
2. **Primal Feasibility**: The constraints must be satisfied: 
 $h_j(x^∗)=0, for j=1,…,ℓ$
 $g_i​(x^∗)≤0, for i=1,…,m$
    
3. **Dual Feasibility**: The Lagrange multipliers for the inequality constraints must be non-negative: $μ_i≥0, for \ i=1,…,m$
    
4. **Complementary Slackness**: The product of the Lagrange multipliers and the inequality constraints must be zero: $μ_ig_i(x^∗)=0, \ for \ i=1,…,m$
    

### Regularity Conditions

Certain regularity conditions (or constraint qualifications) must be met for the KKT conditions to hold. Some common examples include:

- **Linearity Constraint Qualification (LCQ)**: If the constraints are affine functions, no other condition is needed.
- **Linear Independence Constraint Qualification (LICQ)**: The gradients of the active inequality constraints and the gradients of the equality constraints are linearly independent at the solution.
- **Mangasarian-Fromovitz Constraint Qualification (MFCQ)**: The gradients of the equality constraints are linearly independent, and there exists a vector satisfying certain conditions related to the inequality constraints.

### Applications

- **Optimization Algorithms**: Many optimization algorithms can be interpreted as methods for numerically solving the KKT system of equations and inequalities.
- **Economics**: Used in solving constrained optimization problems in economics, such as utility maximization.

### Connection to Other Topics

- **[[Lagrange Multipliers]]**: The KKT conditions generalize the method of Lagrange multipliers, allowing inequality constraints.
- **[[Convex Optimization]]**: The KKT conditions are particularly important in convex optimization, where they provide both necessary and sufficient conditions for optimality.
- [[Optimization]]