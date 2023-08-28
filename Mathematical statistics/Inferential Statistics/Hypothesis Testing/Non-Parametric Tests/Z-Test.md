The Z-test is a statistical test used to determine whether two population means are different when the variances are known and the sample size is large. It is one of the most common statistical tests and is the foundation for many other statistical procedures. Here's a detailed overview:

### Definition

A Z-test is any statistical test for which the distribution of the test statistic under the null hypothesis can be approximated by a normal distribution. Z-tests test the mean of a distribution, and they are often used when the sample size is large or the population variance is known.

### Formula

The Z-test statistic is calculated as: 

$$Z = \frac{\bar{X} - \mu_0}{\sigma / \sqrt{n}}$$
​where Xˉ is the sample mean, μ0 is the population mean under the null hypothesis, σ is the population standard deviation, and nn is the sample size.

### Assumptions

- **Normal Distribution**: The test statistic should follow a normal distribution, often justified by the central limit theorem.
- **Known Population Variance**: The population standard deviation σσ must be known or accurately estimated.
- **Independence**: Observations must be independent.
- **Large Sample Size**: Typically, the sample size should be 50 observations or more.

### Types of Z-Tests

1. **One-Sample Z-Test**: Compares the mean of a set of measurements to a given constant.
2. **Two-Sample Z-Test**: Compares the means of two populations.
3. **Z-Test for Proportions**: Compares proportions between two groups.

### Applications

- **Quality Control**: In industries to check the quality of products.
- **Medical Research**: Comparing the effect of treatments.
- **Economic Studies**: Comparing different economic indicators.

### Advantages and Disadvantages

- **Advantages**: More convenient than the t-test when the population deviation is known.
- **Disadvantages**: Rarely used in practice because the population deviation is difficult to determine.

### Connections to Other Topics

- **t-Test**: The t-test is used when the sample size is small, and the population variance is unknown. It is closely related to the Z-test.
- **Central Limit Theorem**: Justifies the normality assumption for the Z-test.

### Obsidian Links

- [[t-Test]]
- [[Central Limit Theorem]]
- [[Mathematical statistics]]
- [[Hypothesis Testing]]
- [[Nonparametric tests]]