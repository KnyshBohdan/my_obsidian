The Riemann Integral is a foundational concept in real analysis and calculus, providing the first rigorous definition of the integral of a function on an interval. Created by Bernhard Riemann, it is essential for many practical applications and can be evaluated or approximated using various methods, including the fundamental theorem of calculus and numerical integration.

#### Definition:

The Riemann Integral of a real-valued function f(x) over an interval $[a,b]$ is defined as:

$$\int_{a}^{b} f(x) dx$$

The integral is the limit of Riemann sums, which are sums of the form:

$$\sum_{i = 0}^{n - 1} f(t_i) (x_{i + 1} - x_i)$$

where titi​ are sample points in the sub-intervals $[x_i,x_i+1]$.

#### Explanation:

The Riemann Integral aims to approximate the area under the curve of a function by using Riemann sums, which are sums of the areas of rectangles under the curve. As the partition of the interval becomes finer, these sums approach the exact area, provided the function is Riemann-integrable.

#### Examples:

1. **Constant Function**: The Riemann integral of f(x)=1f(x)=1 over [0,1][0,1] is 1.
2. **Indicator Function**: The indicator function of rational numbers in [0,1][0,1] does not have a Riemann integral.

#### Properties:

1. **Mesh**: The mesh of a partition is the length of the longest sub-interval.
2. **Refinement**: One partition is a refinement of another if it breaks up some of the sub-intervals and adds sample points, thereby increasing accuracy.

#### Applications:

1. **Physics**: In calculating work, energy, and other quantities.
2. **Engineering**: In numerical methods for solving real-world problems.

#### Connection to Other Topics:

- [[Integrals]]: The broader concept that includes various types of integrals.
- [[Fundamental Theorem of Calculus]]: Connects differentiation and integration.
- [[Lebesgue Integration]]: A more generalized form of integration.
- [[Numerical Integration]]: Approximate methods for evaluating integrals.
- - [[Integral Calculus]]
- [[Calculus]]