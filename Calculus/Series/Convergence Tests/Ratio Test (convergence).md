The Ratio Test is a powerful method used to determine the convergence or divergence of an infinite series. Developed by Jean le Rond d'Alembert, it is also known as d'Alembert's Ratio Test or the Cauchy Ratio Test. This test is widely used in mathematical analysis and calculus.

#### Definition:

The Ratio Test states that for a series ∑n=1∞an, where each term an​ is a real or complex number and is nonzero for large n, the limit L is defined as:

$$L = \lim_{n \to \infty} |\frac{a_{n + 1}}{a_n}|$$

The series behaves as follows:

- If L<1, the series converges absolutely.
- If L>1, the series diverges.
- If L=1 or the limit fails to exist, the test is inconclusive.

#### Explanation:

The Ratio Test essentially compares the ratio of consecutive terms in the series. If the ratio tends to a limit less than 1, it indicates that the terms of the series are getting smaller fast enough for the series to converge. Conversely, if the limit is greater than 1, the terms are growing, causing the series to diverge.

#### Examples:

- **Convergent Series**: ∑n=1∞nen​ has L=1e<1, hence it converges.
- **Divergent Series**: ∑n=1∞enn has L=e>1, hence it diverges.

#### Properties:

- **Limit Superior and Limit Inferior**: In cases where the limit LL fails to exist, one can use the limit superior and limit inferior to make the test applicable.
- **Inconclusiveness**: When L=1, the test is inconclusive, and more refined tests are required.

#### Applications:

- **Mathematical Analysis**: For studying the convergence of series.
- **Engineering**: In signal processing and control systems.
- **Computer Science**: In algorithms that involve series calculations.

#### Connection to Other Topics:

- [[Comparison Test (convergence)]]: Another method for testing convergence.
- [[Calculus]]: Integral tests and other convergence tests.
- [[Real Analysis]]: Study of infinite series and their properties.
- [[Convergence Tests]]
- [[Sequences and Series]]