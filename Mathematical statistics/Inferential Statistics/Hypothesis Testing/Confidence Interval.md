A Confidence Interval (CI) is a fundamental concept in statistics that provides a range of values used to estimate an unknown population parameter. It's a vital tool in statistical inference, allowing researchers to understand the uncertainty associated with a particular estimate.

### Definition

A confidence interval is a range of values, derived from the statistical data, used to estimate an unknown population parameter. The interval has an associated confidence level that quantifies the level of confidence that the parameter lies in the interval. Common confidence levels include 95%, 90%, and 99%.

The mathematical definition of a confidence interval for a parameter θ with confidence level γγ is an interval (u(X),v(X)), determined by random variables u(X)and v(X), with the property: P(u(X)<θ<v(X))=γ

### Key Concepts

1. **Confidence Level**: The confidence level represents the long-run proportion of CIs that theoretically contain the true value of the parameter. A 95% confidence level means that 95% of the intervals computed from repeated sampling will contain the true parameter.
2. **Width of the CI**: Factors affecting the width of the CI include the sample size, the variability in the sample, and the confidence level. A larger sample and higher confidence level generally produce a wider confidence interval.
3. **Approximate Confidence Intervals**: In many applications, exact intervals are hard to construct, but approximate intervals can be computed.

### Example

Suppose you have a sample from a normally distributed population with unknown mean μμ and variance σ2σ2. The 95% confidence interval for μ can be calculated as: $[xˉ−\frac{c s}{\sqrt{n}},xˉ+\frac{cs}{\sqrt{n}}]$

​ where xˉxˉ is the sample mean, s is the sample standard deviation, n is the sample size, and c is the 97.5th percentile of the Student's t-distribution with n−1 degrees of freedom.

### Applications

1. **Scientific Research**: Used to quantify the uncertainty of an estimate, such as the mean or proportion.
2. **Quality Control**: In industrial settings, CIs are used to assess the reliability of product measurements.
3. **Medical Studies**: Used to estimate parameters like the effectiveness of a treatment or the prevalence of a disease.

### Connections to Other Topics

- **Hypothesis Testing**: Confidence intervals are closely related to hypothesis testing, and the two concepts often complement each other.
- **Bootstrapping**: A resampling method that allows construction of confidence intervals when distributional assumptions are uncertain.
- **Central Limit Theorem**: Often used to justify the construction of confidence intervals for large samples.

### Obsidian Links

- [[Hypothesis Testing]]
- [[Bootstrapping]]
- [[Central Limit Theorem]]
- [[Mathematical statistics]]