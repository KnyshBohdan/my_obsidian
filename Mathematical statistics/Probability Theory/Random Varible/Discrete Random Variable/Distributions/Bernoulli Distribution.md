The Bernoulli Distribution is a discrete probability distribution that models a single experiment with two possible outcomes, often referred to as a "success" or "failure." It is named after Swiss mathematician Jacob Bernoulli and is a fundamental concept in probability theory.

## Definition

The Bernoulli Distribution has two parameters:

- p: The probability of success (value 1).
- q=1−p: The probability of failure (value 0).

### Probability Mass Function (PMF)

$$f(k; p) = \begin{cases} p \ if \ k = 1, \\ q = 1 - p \ if \ k = 0\end{cases}$$
### Cumulative Distribution Function (CDF)

$$\begin{cases} 0 \ if \ k < 0 \\ 1 - p \ if \ 0 \le k \le 1, \\ 1 \ if \ k \ge 1 \end{cases}$$

### Mean

E⁡[X]=p

### Variance

Var⁡[X]=pq=p(1−p)

### Skewness

$$\frac{q - p}{\sqrt{pq}}$$

### Excess Kurtosis

$$\frac{1 - 6pq}{pq}$$

### Entropy

−qln⁡q−pln⁡p

## Example

The Bernoulli Distribution can be used to model a biased coin toss where 1 represents "heads" and 0 represents "tails." If the probability of landing on heads is 0.7, then p=0.7 and q=0.3.

## Connections to Other Topics

- [[Binomial Distribution]]: The Bernoulli Distribution is a special case of the Binomial Distribution where a single trial is conducted.
- [[Probability Theory]]: It is a fundamental concept in Probability Theory.
- [[Random Variable]]: It is a specific type of discrete random variable.
- [[Random Variable]]
- [[Mathematical statistics]]
## Properties

- **Median**: The median is 0 if p<1/2​, 1 if p>1/2​, and $[0,1]$ if p=1/2
- **Mode**: The mode is 0 if p<1/2​, 1 if p>1/2​, and 0,1 if p=1/2​.
- **Moment-Generating Function (MGF)**: $q+pe^t$
- **Characteristic Function (CF)**: $q+pe^{it}$