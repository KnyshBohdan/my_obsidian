Integration by Partial Fractions is a technique used in integral calculus to simplify complex rational functions into simpler fractions that are easier to integrate. This method is particularly useful in solving integrals involving polynomial functions and finds applications in engineering, physics, and computer science.

#### Definition:

The method involves decomposing a given rational function P(x)/Q(x))​ into a sum of simpler fractions:

$$\frac{P(x)}{Q(x)} = \sum_{i = 1}^{n} \frac{A_i}{(x - a_i)^{n_i}}$$
Here, P(x) and Q(x) are polynomials, Ai​ are constants, ai​ are the roots of Q(x) and ni​ are their multiplicities.

#### Explanation:

The technique is based on the principle of decomposing the denominator Q(x) into its irreducible factors. The numerator of each partial fraction is then determined by equating coefficients or using other methods like synthetic division or residue calculation. The resulting simpler fractions can be easily integrated.

#### Examples:

1. **Simple Decomposition**: x+2x2−1=1x−1−1x+1
2. **Repeated Roots**: 2x+3(x−1)2=1x−1+1(x−1)2(x−1)22x+3​=x−11​+(x−1)21​

#### Properties:

1. **Linearity**: The method is linear, meaning it can be applied to each term of a sum of rational functions.
2. **Uniqueness**: The decomposition is unique, given that the degree of P(x)P(x) is less than that of Q(x)Q(x).

#### Applications:

1. **Engineering**: In solving circuits modeled by differential equations.
2. **Computer Science**: In algorithms for symbolic integration.

#### Connection to Other Topics:

- [[Integral Calculus]]: The broader field that includes various methods of integration.
- [[Laplace Transform]]: Partial fractions are used to find inverse Laplace transforms.
- [[Polynomial Long Division]]: Often used to simplify the rational function before applying partial fractions.
- [[Calculus]]