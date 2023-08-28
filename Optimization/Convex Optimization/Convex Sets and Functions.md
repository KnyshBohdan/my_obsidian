#### Description

A convex set is a geometric concept that intuitively captures the idea of "shape without dents." If you imagine a stretched rubber band enclosing a region, the area inside the rubber band is a convex set. This simple idea has profound implications in various mathematical and practical applications.

#### Definition

A set $S$ in a real vector space is called convex if, for any two points $x,y∈S$ the entire line segment connecting them is also in S. Mathematically, this can be expressed as: $∀x,y∈S,∀θ∈[0,1]:θx+(1−θ)y∈S$

### Convex Functions

#### Description

A convex function is a mathematical function that preserves the "shape without dents" property along its domain. If you imagine drawing a line segment between any two points on the graph of the function, the line segment will always lie above the graph. This property ensures that local minima are also global minima, which is vital in optimization problems.

#### Definition

A function $f:R^n→R$ is called convex if its domain is a convex set, and for all $x,y$ in its domain and $θ∈[0,1]$, the following inequality holds: $f(θx+(1−θ)y)≤θf(x)+(1−θ)f(y)$

### Properties

- **Convex Sets**:
    
    - **Intersection**: The intersection of any collection of convex sets is also convex.
    - **Convex Hull**: The smallest convex set containing a given set is called its convex hull.
- **Convex Functions**:
    
    - **First-Order Condition**: A differentiable function is convex if and only if its gradient is monotonically increasing.
    - **Second-Order Condition**: A twice-differentiable function is convex if and only if its second derivative (or Hessian matrix for multivariate functions) is non-negative.

### Applications

- **Convex Sets**: Used in defining feasible regions in optimization problems.
- **Convex Functions**: Fundamental in convex optimization, economics, machine learning, and more.

### Connection to Other Topics

- **[[Optimization]]**: Convex sets and functions are central to convex optimization.
- **[[Economics]]**: Convex functions are used in utility and production functions.
- [[Convex Optimization]]