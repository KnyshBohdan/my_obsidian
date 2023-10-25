The Integral Test for Convergence is a mathematical tool used to assess the convergence of infinite series with monotonous terms. Developed by Colin Maclaurin and Augustin-Louis Cauchy, it is sometimes referred to as the Maclaurin–Cauchy test. This test is crucial in calculus and real analysis for understanding the behavior of series.

#### Definition:

Given a function f(x) defined on an unbounded interval $[N,∞)$ where f(x) is monotone decreasing, the infinite series

$$\sum_{n = N}^{\infty} f(n)$$

converges to a real number if and only if the improper integral

$$\int_{N}^{\infty}f(x) dx$$

is finite.

#### Explanation:

The Integral Test compares the sum of an infinite series to an integral. If the integral is finite, the series converges; if the integral is infinite, the series diverges. The test essentially uses the comparison test, comparing each term of the series with the integral over corresponding intervals.

#### Examples:

- **Harmonic Series**: ∑n=1∞1n∑n=1∞​n1​ diverges because its integral, ∫1∞1x dx∫1∞​x1​dx, is infinite.
- **Series with Power Rule**: ∑n=1∞1n1+ϵ∑n=1∞​n1+ϵ1​ converges for every ϵ>0ϵ>0 because its integral is finite.

#### Properties:

- **Error Bounds**: If the improper integral is finite, the test also provides lower and upper bounds for the infinite series.

#### Applications:

- **Calculus**: Used for determining the convergence of infinite series.
- **Real Analysis**: Integral Test is a part of real analysis, especially in the study of series.

#### Connection to Other Topics:

- [[Convergence Tests]]: Integral Test is one of several tests used to determine series convergence.
- [[Sequences and Series]]
- [[Real Analysis]]: Integral Test is a fundamental concept in real analysis.
- [[Calculus]]