The Alternating Series Test is a method in mathematical analysis used to determine the convergence of an alternating series. This test is particularly useful for series where the terms alternate in sign. It is widely applied in calculus and numerical analysis.

#### Definition:

An alternating series is of the form:

$$∑_{n=0}^{∞}(−1)^n a_n=a_0−a_1+a_2−a_3+⋯$$

The Alternating Series Test guarantees that such a series converges if the following two conditions are met:

1. ∣an∣∣an​∣ decreases monotonically, i.e., $∣a_n+1∣≤∣a_n∣$
2. $\lim_{⁡n→∞}a_n=0$

#### Explanation:

The test was originally used by Gottfried Leibniz and is sometimes known as Leibniz's test or Leibniz's rule. The test is sufficient but not necessary, meaning some convergent alternating series may fail the first part of the test.

#### Examples:

- **Alternating Harmonic Series**: $∑_{n=1}^{∞}\frac{(−1)^{n+1}}{n}$​ meets both conditions and therefore converges.
- **Non-Monotonic Series**: A series like $\sum_{n = 1}^{\infty} (-1)^n \frac{\cos^2(n)}{n^2}$​ may converge even if it doesn't meet the monotonicity condition.

#### Properties:

- **Error Bound**: The error in approximating the sum LL of the series by a partial sum SkSk​ is bounded by the next omitted term ak+1ak+1​, i.e., ∣Sk−L∣≤ak+1∣Sk​−L∣≤ak+1​.

#### Applications:

- **Calculus**: Used in determining the convergence of alternating series.
- **Numerical Analysis**: Employed in algorithms for approximating series sums.

#### Connection to Other Topics:

- [[Convergence Tests]]: The Alternating Series Test is one among various tests for series convergence.
- [[Calculus]]: It is a fundamental concept in calculus.
- [[Mathematical Analysis]]: The test is part of the broader field of mathematical analysis.
- [[Sequences and Series]]