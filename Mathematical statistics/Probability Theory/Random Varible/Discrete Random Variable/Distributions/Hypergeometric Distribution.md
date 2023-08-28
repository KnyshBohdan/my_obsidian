The Hypergeometric Distribution is a discrete probability distribution that describes the probability of kk successes in nn draws without replacement from a finite population of size NN containing exactly KK objects with a specified feature. It contrasts with the binomial distribution, which describes the probability of successes in draws with replacement.

### Definition

The Hypergeometric Distribution is defined by the following parameters:

- N: Total population size.
- K: Number of success states in the population.
- n: Number of draws (i.e., quantity drawn in each trial).
- k: Number of observed successes.

The probability mass function (PMF) is given by:

$$p_X(k) = \frac{\begin{pmatrix} K \\ k\end{pmatrix} \begin{pmatrix} N - K \\ n - k\end{pmatrix}}{ \begin{pmatrix} N \\ n \end{pmatrix}}$$
### Key Concepts

1. **Discrete Distribution**: The distribution is defined for discrete values of kk.
2. **Without Replacement**: The draws are made without replacement, so the probability of success changes on each draw.
3. **Two Categories**: The result of each draw can be classified into one of two mutually exclusive categories (e.g., Pass/Fail).
4. **Support**: The PMF is positive when max⁡(0,n+K−N)≤k≤min⁡(K,n)

### Example

Consider an urn with 50 marbles, 5 green (success) and 45 red (failure). If you draw 10 marbles without replacement, the probability of drawing exactly 4 green marbles is: 

$$P(X = 4) = \frac{\begin{pmatrix} 5 \\ 4\end{pmatrix} \begin{pmatrix} 45 \\ 6\end{pmatrix}}{\begin{pmatrix} 50 \\ 10\end{pmatrix}}  \approx 0.003964583$$
### Applications

1. **Statistical Testing**: Used in Fisher's Exact Test and other statistical significance tests.
2. **Sampling without Replacement**: Models situations where sampling is done without replacement, such as drawing cards from a deck.
3. **Genetics and Ecology**: Used to model gene frequencies and species sampling.

### Connections to Other Topics

- **Binomial Distribution**: If drawing with replacement, the binomial distribution is used instead.
- **Multivariate Hypergeometric Distribution**: An extension to more than two categories.
- **Negative Hypergeometric Distribution**: Describes the number of failures before the last success in a sequence of draws.

### Obsidian Links

- [[Fisher's Test]]
- [[Binomial Distribution]]
- [[Multivariate Hypergeometric Distribution]]
- [[Negative Hypergeometric Distribution]]
- [[Discrete Random Variable]]
- [[Random Variable]]
- [[Mathematical statistics]]