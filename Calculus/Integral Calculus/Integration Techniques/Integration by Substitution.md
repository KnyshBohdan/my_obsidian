Integration by Substitution is a method used to simplify complex integrals by transforming them into more manageable forms. This technique is particularly useful when the integral involves composite functions or when the integrand can be rewritten to simplify the integration process.

### Definition

The basic idea behind Integration by Substitution is to substitute a part of the integrand with a new variable, say u, such that u=g(x). Then, du=g′(x)dx. The integral then transforms as follows:

$$∫f(g(x))⋅g′(x) dx=∫f(u) du$$

### Properties and Characteristics

- **Change of Variables**: The method essentially involves a change of variables to simplify the integral.
- **Bi-Lipschitz Mapping**: For more complex cases involving Lipschitz functions, the Jacobian determinant comes into play, further generalizing the method.
- **Measurability**: The method is well-defined for Lebesgue integrable functions, extending its applicability beyond Riemann integrals.

### Examples

1. **Basic Polynomial**: ∫xsin⁡(x2) dx
2. **Trigonometric Functions**: ∫tan⁡(x) dx

### Applications

- **Physics**: Used in solving problems involving motion and energy.
- **Engineering**: Applied in signal processing and control theory.
- **Statistics**: Useful in probability density transformations.

### Connection to Other Topics

- **[[Differential Calculus]]**: The method is essentially the reverse process of the Chain Rule in differentiation.
- **[[Lebesgue Integration]]**: The method extends to Lebesgue integrals, making it relevant in measure theory.
- **[[Probability Theory]]**: In probability, the method is used to find the density of transformed random variables.
- - [[Integral Calculus]]
- [[Calculus]]