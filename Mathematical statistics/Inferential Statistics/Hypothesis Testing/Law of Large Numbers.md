The Law of Large Numbers (LLN) is a fundamental theorem in probability theory that describes the behavior of the average of a large number of independent and identically distributed (i.i.d.) random variables. It asserts that as the number of trials increases, the average of the results will converge to the expected value.

### Definition

The LLN can be expressed in two forms: the Weak Law of Large Numbers (WLLN) and the Strong Law of Large Numbers (SLLN).

1. **Weak Law of Large Numbers**: The sample average converges in probability towards the expected value. Mathematically: 
$$\lim_{n \to \infty} Pr(|\frac{\sum_{i = 1}^{n}(X_i - \mu)}{n}| < \varepsilon) = 1$$
for any positive number ε, where Xi are i.i.d. random variables with expected value μ.
    
2. **Strong Law of Large Numbers**: The sample average almost surely converges to the expected value. This is a stronger form of convergence compared to the weak law.

### Key Concepts

1. **Independence and Identical Distribution**: The random variables must be independent of each other and have the same probability distribution.
2. **Convergence to Expected Value**: The average of the random variables converges to the expected value as the number of trials increases.
3. **Applicability**: The LLN applies to random variables with finite expected values. Some distributions, such as the Cauchy distribution, may not satisfy the conditions of the LLN.

### Example

Consider a fair six-sided die. The expected value of a single roll is 1+2+3+4+5+6​=3.5. According to the LLN, if a large number of six-sided dice are rolled, the average of their values will approach 3.5, with the precision increasing as more dice are rolled.

### Applications

1. **Gambling and Casinos**: Explains why casinos tend to win over time, even though they may lose in individual games.
2. **Monte Carlo Methods**: Utilized in computational algorithms that rely on repeated random sampling to obtain numerical results.
3. **Statistical Analysis**: Underpins many statistical methods, ensuring that sample statistics converge to population parameters.

### Connections to Other Topics

- **Central Limit Theorem**: While the LLN describes the convergence of the mean, the Central Limit Theorem describes the distribution around the mean.
- **Bernoulli Trials**: The LLN applies to Bernoulli trials, where the empirical probability of success will converge to the theoretical probability.

### Obsidian Links

- [[Central Limit Theorem]]
- [[Mathematical statistics]]