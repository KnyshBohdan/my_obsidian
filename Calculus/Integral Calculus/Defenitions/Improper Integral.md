Improper integrals are a type of integral that involve either an infinite interval of integration or a function with an infinite discontinuity within the interval of integration. They extend the concept of a definite integral to cases where standard methods of integration do not apply.

## Definition

An improper integral is formally defined as a limit. For example, the integral of f(x) from aa to ∞ is defined as:

$$\int_{a}^{\infty} f(x) dx = \lim_{b \to \infty} \int_{a}^{b} f(x) dx$$

Similarly, if f(x) has an infinite discontinuity at cc within $[a,b]$, then:

$$\int_{a}^{b} f(x) dx = \lim_{\epsilon \to 0^+}(\int_{a}^{c - \epsilon} f(x) dx + \int_{c + \epsilon}^{b} f(x) dx)$$

## Examples

1. **Integral of 1/x​ from 1 to ∞∞**: This is an example of an improper integral with an infinite limit, and it diverges.
2. **Integral of 1x2x21​ from 0 to 1**: This is an example of an improper integral with an infinite discontinuity at x=0x=0, and it converges.

## Properties

- **Convergence**: An improper integral converges if the limit defining it exists; otherwise, it diverges.
- **Comparison Test**: If 0≤f(x)≤g(x)0≤f(x)≤g(x) and ∫a∞g(x) dx∫a∞​g(x)dx converges, then ∫a∞f(x) dx∫a∞​f(x)dx also converges.

## Applications

- **Probability Theory**: Improper integrals are often used in defining continuous probability distributions.
- **Engineering**: Used in various applications like signal processing and systems analysis.
- **Physics**: Appear in problems involving infinite potentials or fields.

## Connections

1. **[[Calculus]]**: Improper integrals are an advanced topic in calculus.
2. **[[Limits]]**: The definition of an improper integral inherently involves limits.
3. **[[Series]]**: Comparison between series and improper integrals can be made using tests for convergence.
4. **[[Differential Equations]]**: They often appear as solutions to differential equations involving non-compact domains.
5. - [[Integral Calculus]]
- [[Calculus]]