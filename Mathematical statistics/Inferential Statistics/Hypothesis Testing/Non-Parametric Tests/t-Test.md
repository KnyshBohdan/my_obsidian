The t-test is a widely used statistical hypothesis test that compares the means of two groups to determine if the differences between them are statistically significant. Here's a comprehensive overview:

### Definition

A t-test is a type of statistical analysis used to compare the averages of two groups and determine if the differences between them are more likely to arise from random chance. The test statistic follows a Student's t-distribution under the null hypothesis.

### History

The t-test was developed by William Sealy Gosset, who published it under the pseudonym "Student." Gosset worked at the Guinness Brewery in Dublin, Ireland, and devised the t-test as an economical way to monitor the quality of stout.

### Types of t-Tests

1. **One-Sample t-Test**: Tests whether the mean of a population has a specified value.
2. **Two-Sample t-Test**: Tests whether the means of two populations are different. It can be:
    - **Unpaired (Independent Samples) t-Test**: Used when two separate sets of independent samples are obtained.
    - **Paired t-Test**: Used when the samples are matched pairs or tested twice (repeated measures).

### Assumptions

- **Normal Distribution**: The means of the populations should follow normal distributions. This is often approximated by the central limit theorem in large samples.
- **Equal Variances**: If using Student's original definition, the two populations should have the same variance (testable using F-test, Levene's test, etc.).
- **Independence**: The observations within and between groups must be independent.

### Formula

For a one-sample t-test, the test statistic is calculated as: 

$$t = \frac{\bar{x} - \mu_0}{s/\sqrt{n}}$$
where xˉ is the sample mean, ss is the sample standard deviation, nn is the sample size, and μ0 is the specified population mean.

### Applications

- **Medical Research**: Comparing the effect of treatments.
- **Quality Control**: In industries to check the quality of products.
- **Educational Research**: Comparing the means of different teaching methods.

### Advantages and Disadvantages

- **Advantages**: It is a robust test that can be used even when the data are not perfectly normal.
- **Disadvantages**: Sensitivity to outliers and assumptions about the distribution and variance.

### Connections to Other Topics

- **F-Test**: Used to test the equality of variances, which is an assumption in some t-tests.
- **Central Limit Theorem**: Allows the use of the t-test even when the population distribution is not normal.

### Obsidian Links

* [[Nonparametric tests]]
* [[Hypothesis Testing]]
- [[F-Test]]
- [[Central Limit Theorem]]
- [[Mathematical statistics]]