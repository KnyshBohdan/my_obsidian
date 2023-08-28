The Kolmogorov–Smirnov test (K–S test or KS test) is a nonparametric test used to compare one-dimensional probability distributions. It can be applied to test the equality of continuous or discontinuous distributions, either by comparing a sample with a reference probability distribution (one-sample K–S test) or by comparing two samples (two-sample K–S test).

### Definition

The Kolmogorov–Smirnov statistic quantifies the distance between the empirical distribution function of the sample and the cumulative distribution function of the reference distribution, or between the empirical distribution functions of two samples.

### One-Sample Kolmogorov–Smirnov Statistic

The one-sample K–S statistic for independent and identically distributed (i.i.d.) ordered observations Xi is defined as: 
$$D_n = sup_z |F_n(x) - F(x)|$$
where Fn(x) is the empirical distribution function, and F(x) is the cumulative distribution function of the reference distribution.

### Two-Sample Kolmogorov–Smirnov Test

The two-sample K–S test compares two underlying one-dimensional probability distributions. The statistic is: 
$$D_{n, m} = sup_z|F_{1, n}(x) - F_{2, n}(x)|$$
where F1,n​ and F2,m​ are the empirical distribution functions of the first and second samples, respectively.

### Applications

- **Goodness of Fit**: The K–S test can be modified to serve as a goodness-of-fit test, including testing for normality.
- **Comparing Two Samples**: The two-sample K–S test is a general nonparametric method for comparing two samples, sensitive to differences in both location and shape.

### Advantages and Disadvantages

- **Advantages**: The K–S test is distribution-free and does not require specific assumptions about the parameters of the distribution.
- **Disadvantages**: The test requires a relatively large number of data points to properly reject the null hypothesis. It may be less powerful for testing normality compared to other tests like the Shapiro–Wilk test.

### Connections to Other Topics

- **Nonparametric Tests**: The K–S test is part of the family of nonparametric tests.
- **Goodness-of-Fit Tests**: It can be used to test how well a sample fits a specific distribution.

### Obsidian Links

- [[Nonparametric Tests]]
- [[Goodness-of-Fit Tests]]
- [[Hypothesis Testing]]
- [[Mathematical statistics]]