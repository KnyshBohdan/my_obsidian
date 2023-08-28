Duality Theory is like the yin and yang of optimization. It provides a way to understand one optimization problem by examining another related problem. It's a principle that has profound implications for both theory and practice in optimization.

## Definition

In mathematical optimization, duality refers to the principle that optimization problems can be viewed from either of two perspectives: the primal problem or the dual problem. If the primal is a minimization problem, then the dual is a maximization problem, and vice versa.

## Mathematical Formulation

### Primal Problem

Maximize $z = \sum_{j = 1}^n c_jx_j$
Subject to:

$$\begin{align} \sum_{j = 1}^n a_{i, j} \le b_i \  \ (i = 1, 2, ..., m) \\ x_j \ge 0 \ \ (j = 1, 2, ..., n)\end{align}$$

### Dual Problem

Minimize $v = \sum_{i=1}^m b_iy_i$
Subject to:

$$\begin{align} \sum_{i=1}^m y_i a_{i, j} \ge c_j \ (j = 1, 2, ..., n) \\ y_i \ge \ (i = 1, 2, ..., m) \end{align}$$

## Properties

- **Weak Duality**: Any feasible solution to the primal problem is at least as large as any feasible solution to the dual problem.
- **Strong Duality**: For convex optimization problems, the duality gap is zero under a constraint qualification condition.

## Applications

- **Resource Allocation**: Dual problems can be used to find upper or lower bounds on the optimal value of the primal problem.
- **Game Theory**: Duality theory has applications in solving two-person zero-sum matrix games.

## Connection to Other Topics

- **[[Linear Optimization]]**: Duality theory is often used in the context of linear optimization to find optimal solutions.
- **[[Convex Optimization]]**: Strong duality is a special case in convex optimization.
- [[Optimization]]