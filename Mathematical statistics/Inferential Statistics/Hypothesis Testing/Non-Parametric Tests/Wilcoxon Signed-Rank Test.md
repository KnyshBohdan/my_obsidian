The Wilcoxon signed-rank test is a non-parametric statistical hypothesis test used to compare the locations of two populations using two matched samples or to test the location of a population based on a sample of data. It serves a purpose similar to the one-sample Student's t-test and is a paired difference test like the paired Student's t-test.

### Definition

The Wilcoxon signed-rank test can be applied in two scenarios:

1. **One-Sample Test**: To test whether data comes from a symmetric population with a specified median.
2. **Paired Data Test**: To compare the locations of two populations using two matched samples.

### Test Procedure

The test procedure involves the following steps:

1. **Compute Absolute Values**: Compute the absolute values of the samples.
2. **Sort and Rank**: Sort the absolute values and assign ranks.
3. **Calculate Test Statistic**: The test statistic is the signed-rank sum: 
$$T = \sum_{i = 1}^{N} sgn(X_i) R_i$$
 where sgn⁡(x)sgn(x) is the sign function, and RiRi​ is the rank of the ii-th observation.
4. **Produce p-value**: Compare the test statistic to its distribution under the null hypothesis.

### Null and Alternative Hypotheses

- **One-Sample Test**: The null hypothesis is that the data comes from a symmetric population with a specified median. The alternative hypothesis can be one-sided or two-sided, testing whether the median is different from the specified value.
- **Paired Data Test**: The null hypothesis is that the observations are symmetric about a specified value, and the alternative hypothesis tests whether this is not the case.

### Zeros and Ties

In real data, there might be samples that equal zero or tied samples. This can complicate the ranking process, and special care must be taken to handle these cases.

### Advantages

- **Non-Parametric**: Does not assume a specific distribution for the data.
- **Robust**: Can be a good alternative to the t-test when population means are not of interest or when assumptions of the t-test are not met.

### Connections to Other Topics

- **Nonparametric Tests**: The Wilcoxon signed-rank test is part of the family of nonparametric tests.
- **Rank-Sum Test**: The test is closely related to the rank-sum test for two independent samples.

### Obsidian Links

- [[Nonparametric Tests]]
- [[Rank-Sum Test]]
- [[Hypothesis Testing]]
- [[Mathematical statistics]]