The Exponential Distribution, or negative exponential distribution, is the probability distribution of the time between events in a Poisson point process, where events occur continuously and independently at a constant average rate. It is a particular case of the gamma distribution and is the continuous analogue of the geometric distribution.

## Definition

The probability density function (pdf) of an exponential distribution is given by:

$$f(x; \lambda) = \begin{cases} \lambda e^{- \lambda x} \ x \ge 0, \\ 0 \ x < 0 \end{cases}$$

Here, λ>0 is the parameter of the distribution, often called the rate parameter. The distribution is supported on the interval $[0,∞)$.

The cumulative distribution function (CDF) is given by:

$$f(x; \lambda) = \begin{cases}1 - e^{- \lambda x} \ x \ge 0, \\ 0 \ x < 0 \end{cases}$$

## Properties

- **Mean**: $1/\lambda$
- **Median**: ln⁡2/λ​
- **Mode**: 0
- **Variance**: $1/λ^2$
- **Skewness**: 2
- **Excess Kurtosis**: 6
- **Entropy**: 1−ln⁡λ

### Memorylessness Property

An exponentially distributed random variable TT obeys the relation:

$$Pr(T > s + t|T > s) = Pr(T > t), \ \forall s, t \ge 0$$

This property implies that the distribution of the remaining waiting time is the same as the original unconditional distribution.

## Applications

The exponential distribution is used for the analysis of Poisson point processes and is found in various other contexts. It has the key property of being memoryless, making it suitable for modeling the time between successive events.

## Connections to Other Topics

- [[Continuous Random Variables]]: The Exponential Distribution is a specific type of continuous random variable.
- [[Poisson Distribution]]: It is related to the time between events in a Poisson process.
- [[Mathematical statistics]]: It is widely used in Mathematical Statistics for various applications.
- [[Random Variable]]
- [[Probability Theory]]