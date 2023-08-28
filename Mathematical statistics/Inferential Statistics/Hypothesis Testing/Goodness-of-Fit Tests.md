Goodness-of-fit tests are statistical procedures used to assess how well a statistical model fits a set of observations. These tests are essential in determining whether a specific distribution or model adequately represents the underlying data. Here's an overview:

### Definition

The goodness of fit of a statistical model describes how well it fits a set of observations. Measures of goodness of fit typically summarize the discrepancy between observed values and the values expected under the model in question.

### Types of Goodness-of-Fit Tests

1. **Kolmogorov–Smirnov Test**: Compares a sample with a reference probability distribution or two samples with each other.
2. **Cramér–von Mises Criterion**: Another method to test the fit of a distribution.
3. **Anderson–Darling Test**: A modification of the Kolmogorov–Smirnov test that gives more weight to the tails.
4. **Shapiro–Wilk Test**: Specifically used to test for normality.
5. **Chi-Squared Test**: Tests whether outcome frequencies follow a specified distribution.
6. **Akaike Information Criterion (AIC)** and **Bayesian Information Criterion (BIC)**: Criteria for model selection.
7. **Hosmer–Lemeshow Test**: Used in logistic regression.
8. **Kuiper's Test**: Another test for comparing distributions.
9. **Kernelized Stein Discrepancy**: A modern method for goodness-of-fit testing.
10. **G-Test**: A likelihood-ratio test used in situations where Pearson's chi-square tests were previously recommended.

### Applications

- **Testing for Normality**: Assessing whether a sample comes from a normal distribution.
- **Comparing Distributions**: Testing whether two samples are drawn from identical distributions.
- **Regression Analysis**: Evaluating the fit of regression models.
- **Categorical Data Analysis**: Assessing the fit of models for categorical data.

### Example: Chi-Square Goodness-of-Fit Test

The chi-square goodness-of-fit test is used to compare observed frequencies with expected frequencies. The test statistic is: 
$$\chi^2 = \sum_{i = 1}^{n} \frac{(O_i - E_i)^2}{E_i}$$
where Oi​ is the observed count for bin i, and Ei is the expected count for bin i, asserted by the null hypothesis.

### Connections to Other Topics

- **Regression Analysis**: Goodness-of-fit measures are essential in regression validation.
- **Nonparametric Tests**: Many goodness-of-fit tests are nonparametric, such as the Kolmogorov–Smirnov test.

### Obsidian Links
* [[Hypothesis Testing]]
- [[Kolmogorov–Smirnov Test]]
- [[Chi-Squared Test]]
- [[Regression Analysis]]