The Root Test is a mathematical criterion used to determine the convergence or divergence of an infinite series. Developed by Augustin-Louis Cauchy, it is particularly useful for power series and is sometimes known as Cauchy's Radical Test. The test is a cornerstone in the field of mathematical analysis.

#### Definition:

The Root Test is defined using the limit superior (lim sup⁡) of the n-th root of the absolute value of the terms of the series ∑n=1∞an​. The test uses the number C defined as:

$$C = \limsup_{n \to \infty} \sqrt[n]{|a_n|}$$


The series behaves as follows:

- If C<1, the series converges absolutely.
- If C>1, the series diverges.
- If C=1, the test is inconclusive.

#### Explanation:

The Root Test examines the nn-th root of the absolute value of the terms of the series. If this root tends to a limit less than 1, the series converges. If it tends to a limit greater than 1, the series diverges. The test is particularly useful for power series, where it can be applied to the coefficients of the series.

#### Examples:

- **Convergent Series**: ∑i=1∞1i9∑i=1∞​i91​ has C=1<1C=1<1, hence it converges.
- **Divergent Series**: ∑i=1∞2ii9∑i=1∞​i92i​ has C=2>1C=2>1, hence it diverges.

#### Properties:

- **Limit Superior**: The test uses the limit superior, which makes it robust against oscillations in the terms of the series.
- **Inconclusiveness**: When C=1C=1, the test is inconclusive, requiring other tests for a definitive answer.

#### Applications:

- **Mathematical Analysis**: For studying the convergence of series.
- **Engineering**: In signal processing and control systems.
- **Computer Science**: In algorithms that involve series calculations.

#### Connection to Other Topics:

- [[Ratio Test (convergence)]]: Another method for testing convergence.
- [[Power Series]]: Where the Root Test is often applied.
- [[Real Analysis]]: Study of infinite series and their properties.
- [[Convergence Tests]]
- [[Calculus]]
- [[Sequences and Series]]