The Rank-Sum Test, also known as the Mann–Whitney U test, is a nonparametric test that compares two unpaired groups of data. It is used to test the null hypothesis that two samples come from the same population (i.e., they have the same distribution).

### Definition

The Rank-Sum Test is based on ranking all the observations from both groups together and then summing the ranks for the observations that belong to one of the groups. The test statistic is the sum of the ranks, and it follows a specific distribution under the null hypothesis.

### Formula

The test statistic for the Mann–Whitney U test can be calculated using the following formula: 
$$U = n_1 n_2 + \frac{n_1(n_1 + 1)}{2} - R_1$$
where n1​ and n2​ are the sample sizes of the two groups, and R1​ is the sum of the ranks in group 1.

### Assumptions

- **Independence**: Observations within and between groups must be independent.
- **Ordinal Data**: The data must be at least ordinal, meaning that it can be put into a meaningful order.
- **Shape of Distributions**: The test does not assume that the distributions have the same shape.

### Applications

- **Comparing Two Independent Samples**: The Rank-Sum Test is used to compare two independent samples to see if they come from the same distribution.
- **Robustness**: The test is less sensitive to outliers compared to the t-test.

### Advantages and Disadvantages

- **Advantages**: It does not require the assumption of normality and is less affected by outliers.
- **Disadvantages**: It may have less power than the t-test when the normality assumption holds.

### Connections to Other Topics

- **Nonparametric Tests**: The Rank-Sum Test is a type of nonparametric test.
- **Wilcoxon Signed-Rank Test**: This is a related test used for paired data.
- **Kruskal–Wallis One-Way Analysis of Variance**: An extension of the Mann–Whitney U test for more than two groups.

### Obsidian Links

- [[Nonparametric Tests]]
- [[Hypothesis Testing]]
- [[Mathematical statistics]]
- [[Wilcoxon Signed-Rank Test]]
- [[Kruskal–Wallis One-Way Analysis of Variance]]