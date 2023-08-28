The Binomial Distribution is a discrete probability distribution that describes the number of successes in a fixed number of independent Bernoulli trials, each with the same probability of success.

## Definition

The Binomial Distribution is denoted by B(n,p), where nn is the number of trials, and pp is the success probability for each trial.

### Probability Mass Function (PMF)

$$Pr(X = k) = \begin{pmatrix} n \\ k \end{pmatrix} p^k(1 - p)^{n - k}$$

for k=0,1,2,…,n

### Cumulative Distribution Function (CDF)

$$F(k; n, p) = \sum_{i = 0}^{[k]} \begin{pmatrix} n \\ i \end{pmatrix} p^i (1 - p)^{n - i}$$

### Mean

$$E[X] = np$$

### Variance

$$Var(X) = np(1 - p)$$

### Skewness

$$\frac{q - p}{\sqrt{npq}}$$

### Entropy

$$\frac{1}{2}log_2(2\pi e n p q) + O(\frac{1}{n})$$

## Example

Suppose a biased coin comes up heads with probability 0.3 when tossed. The probability of seeing exactly 4 heads in 6 tosses is given by:

$$f(4, 6, 0.3) = \begin{pmatrix} 6 \\ 4 \end{pmatrix}0.3^4 (1 - 0.3)^{6 - 4} = 0.059535$$

## Properties

- **Expected Value and Variance**: The expected value is npnp, and the variance is np(1−p)np(1−p).
- **Mode**: The mode can be calculated based on the value of nn and pp.
- **Median**: The median may be non-unique and can be calculated based on special results.
- **Tail Bounds**: Various bounds can be derived for the lower and upper tail of the cumulative distribution function.

## Connections to Other Topics

- [[Probability Theory]]: The Binomial Distribution is a fundamental concept in Probability Theory.
- [[Random Variable]]: It is a specific type of discrete random variable.
- [[Bernoulli Distribution]]: A single success/failure experiment is a Bernoulli experiment, and the Binomial Distribution generalizes this for multiple trials.
- [[Mathematical statistics]]: It is widely used in Mathematical Statistics for various applications.
- [[Discrete Random Variable]]