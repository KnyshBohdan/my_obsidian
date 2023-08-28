A test statistic is a statistic (a quantity derived from the sample) used in statistical hypothesis testing. It serves as a numerical summary of a dataset that reduces the data to one value, which can be used to perform the hypothesis test.

## Definition

A test statistic is selected or defined to quantify, within observed data, behaviors that would distinguish the null from the alternative hypothesis. An essential property of a test statistic is that its sampling distribution under the null hypothesis must be calculable, either exactly or approximately, allowing p-values to be calculated.

## Key Concepts

### 1. **T-Statistic and F-Test**: Two widely used test statistics.

### 2. **Sampling Distribution**: Must be known under the null hypothesis.

### 3. **Descriptive Statistic**: Shares qualities with descriptive statistics but is specifically intended for use in statistical testing.

## Example

Suppose the task is to test whether a coin is fair. If the coin is flipped 100 times, the raw data can be represented as a sequence of 100 heads and tails. The number of tails out of the 100 flips can be used as a test statistic in two ways:

- The exact distribution of tails under the null hypothesis is the binomial distribution with parameters 0.5 and 100.
- The value of tails can be compared with its expected value under the null hypothesis of 50, using a normal distribution as an approximation.

## Common Test Statistics

- **Z-Tests**: Appropriate for comparing means under stringent conditions regarding normality and a known standard deviation.
- **T-Test**: Appropriate for comparing means under relaxed conditions.
- **Chi-Squared Tests**: Used for variance, independence, and goodness of fit.
- **F-Tests**: Used in analysis of variance (ANOVA) for deciding whether groupings of data by category are meaningful.
- **Regression T-Test**: Used for testing the coefficient of determination.

## Connections to Other Topics

- [[Hypothesis Testing]]: Test statistics are integral to Hypothesis Testing.
- [[Type I Error]]: Related to the probability of making a Type I Error.
- [[Type II Error]]: Related to the probability of making a Type II Error.
- [[Two-Tailed Test]]: Test statistics can be used in both one-tailed and two-tailed t
- [[Mathematical statistics]]