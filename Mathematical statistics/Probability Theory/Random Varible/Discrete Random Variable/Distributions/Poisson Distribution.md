
The Poisson Distribution is a discrete probability distribution that models the number of events occurring in a fixed interval of time or space. These events must occur with a known constant mean rate and independently of the time since the last event.

## Definition

The Poisson Distribution is denoted by Pois⁡(λ), where λ is the expected rate of occurrences (mean).

### Probability Mass Function (PMF)

The PMF is given by:

$$\frac{\lambda ^k e^{-\lambda}}{k!}$$

### Cumulative Distribution Function (CDF)

The CDF is expressed as:

$$e^{- \lambda}\sum_{j = 0}^{[k]} \frac{\lambda^{j}}{j!}$$

### Mean

The mean of the distribution is:

$$\lambda$$

### Variance

The variance is given by:

$$\lambda$$

### Skewness

The skewness is:

$$\frac{1}{\sqrt{\lambda}}$$
### Entropy

The entropy of the distribution is:

$$\lambda [1 - log(\lambda)] + e^{- \lambda} \sum_{k = 0}^{\infty} \frac{\lambda^{k} log(k!)}{k!}$$

## Examples

### Call Center

A call center receives an average of 180 calls per hour, 24 hours a day. The calls are independent, and the number of calls received during any minute has a Poisson probability distribution with mean 3.

### Radioactive Decay

Another example is the number of decay events that occur from a radioactive source during a defined observation period.

## Assumptions and Validity

The Poisson distribution is an appropriate model if the following assumptions are true:

- The occurrence of one event does not affect the probability that a second event will occur (independence).
- The average rate at which events occur is independent of any occurrences (constant rate).
- Two events cannot occur at exactly the same instant.

## Connections to Other Topics

- [[Discrete Random Variable]]: The Poisson Distribution is a specific type of discrete random variable.
- [[Probability Theory]]: This distribution plays a vital role in Probability Theory, especially in modeling rare events.
- [[Mathematical statistics]]: It is widely used in Mathematical Statistics for various applications.
- [[Random Variable]]