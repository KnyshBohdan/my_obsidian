The Central Limit Theorem (CLT) is a fundamental principle in probability theory and statistics. It establishes that, under certain conditions, the sum of a large number of independent and identically distributed (i.i.d.) random variables will tend to follow a normal distribution, regardless of the underlying distribution of the individual variables.

### Definition

The CLT states that if X1,X2,…,Xn are i.i.d. random variables with mean μμ and finite variance σ2, then the standardized sample mean will converge to the standard normal distribution as the sample size nn approaches infinity. Mathematically:

​$$\frac{\bar{X_n} - \mu}{\sigma/\sqrt{n}} \to^d N(0, 1)$$

### Key Concepts

1. **Independence**: The random variables must be independent of each other.
2. **Identically Distributed**: The random variables must have the same probability distribution.
3. **Normal Approximation**: The theorem allows the use of normal distribution approximations for problems involving other types of distributions.
4. **Sample Size**: The approximation improves as the sample size increases.

### Variants

- **Lindeberg–Lévy CLT**: Applies to i.i.d. random variables with finite mean and variance.
- **Lyapunov CLT**: Allows for non-identically distributed variables, provided certain conditions are met.
- **Multidimensional CLT**: Extends the theorem to random vectors in RkRk, converging to a multivariate normal distribution.

### Example

Consider a random sample from a population with any distribution, having mean μμ and variance σ2. If the sample size is large enough, the distribution of the sample mean will be approximately normal with mean μ and variance σ2/n.

### Applications

1. **Statistical Inference**: Enables the use of normal distribution methods for various statistical tests and confidence intervals.
2. **Quality Control**: Used in industrial settings to monitor process stability.
3. **Finance**: Applied in portfolio theory to model returns.

### Connections to Other Topics

- **Law of Large Numbers**: CLT can be seen as an extension, describing the distribution around the mean.
- **Binomial Distribution**: De Moivre–Laplace theorem, a specific case of CLT, applies to binomial distributions.
- **Hypothesis Testing**: CLT is fundamental in constructing statistical tests for large samples.

### Obsidian Links

- [[Law of Large Numbers]]
- [[Binomial Distribution]]
- [[Hypothesis Testing]]
- [[Mathematical statistics]]