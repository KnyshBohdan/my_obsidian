The Geometric Distribution is a discrete probability distribution that describes the number of Bernoulli trials needed to get one success. It can be defined in two ways:

1. **Number of Trials (including success):** The probability distribution of the number X of Bernoulli trials needed to get one success, supported on the set {1,2,3,…}.
2. **Number of Failures before success:** The probability distribution of the number Y of failures before the first success, supported on the set {0,1,2,…}.

## Definition

The Geometric Distribution is denoted by Geo(p), where 0<p≤1 is the success probability.

### Probability Mass Function (PMF)

- For the number of trials (including success): $Pr⁡(X=k)=(1−p)^{k−1}p$, for k=1,2,3,4,…
- For the number of failures before success: $Pr⁡(Y=k)=(1−p)^kp$, for k=0,1,2,3,…

### Cumulative Distribution Function (CDF)

- For $x \ge 1:1 - (1-p)^{[x]}$
- For $x \ge 0:1 - (1-p)^{[x] + 1}$

### Mean

- For the number of trials (including success): $1/p$​.
- For the number of failures before success: $(1-p)/p$​.

### Variance

$$\frac{1 - p}{p^2}$$
### Skewness

$$\frac{2 - p}{\sqrt{1 - p}}$$

### Entropy

$$\frac{-(1-p)log(1-p) - p log(p)}{p}$$

## Examples

### Throwing a Die

Suppose an ordinary die is thrown repeatedly until the first time a "1" appears. The probability distribution of the number of times it is thrown is supported on the infinite set {1,2,3,…} and is a geometric distribution with p=16p=61​.

### Medical Treatment

A doctor is seeking an antidepressant for a newly diagnosed patient. Suppose that, of the available anti-depressant drugs, the probability that any particular drug will be effective for a particular patient is p=0.6. The geometric distribution can model the number of drugs that will be tried to find one that is effective.

## Properties

- **Memoryless Property**: The geometric distribution supported on {1,2,3,…}} is memoryless.
- **Largest Entropy**: Among all discrete probability distributions supported on {1,2,3,…} with a given expected value, the geometric distribution has the largest entropy.
- **Infinitely Divisible**: The geometric distribution of the number of failures before the first success is infinitely divisible.

## Connections to Other Topics

- [[Discrete Random Variable]]: The Geometric Distribution is a specific type of discrete random variable.
- [[Probability Theory]]: This distribution is fundamental in Probability Theory, especially in modeling the number of trials until the first success.
- [[Mathematical statistics]]: It is widely used in Mathematical Statistics for various applications.
- [[Random Variable]]