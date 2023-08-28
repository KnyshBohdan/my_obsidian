The Mann–Whitney U test, also known as the Mann–Whitney–Wilcoxon (MWW/MWU) test, Wilcoxon rank-sum test, or Wilcoxon–Mann–Whitney test, is a nonparametric statistical test used to test the null hypothesis that two independent samples come from the same distribution. It is widely applied when comparing two independent samples, especially when the data are not normally distributed.

### Definition

The Mann–Whitney U test is based on the following assumptions:

1. **Independence**: All observations from both groups are independent of each other.
2. **Ordinal Data**: The responses are at least ordinal, meaning one can say, of any two observations, which is the greater.
3. **Null Hypothesis**: Under the null hypothesis H0​, the distributions of both populations are identical.

The alternative hypothesis is that the distributions are not identical.

### U Statistic

The U statistic is defined as the smaller of two values, calculated based on the sum of the ranks in the two groups. It can be expressed as: 
$$U = n_1 n_2 + \frac{n_1(n_1 + 1)}{2} - R_1 \ or \ U = n_1 n_2 + \frac{n_2(n_2 + 1)}{2} - R_2$$
where R1,R2​ are the sum of the ranks in groups 1 and 2, respectively.

### Calculations

The test involves the calculation of the U statistic, whose distribution under the null hypothesis is known. For small samples, the distribution is tabulated, but for sample sizes above ~20, approximation using the normal distribution is fairly good.

### Example

Suppose you have two groups of data representing the scores of two different classes on a test. By applying the Mann–Whitney U test, you can determine whether the two classes have significantly different performance levels.

### Applications

1. **Medical Research**: Comparing the effects of two different treatments.
2. **Social Sciences**: Assessing the impact of an intervention on two different groups.
3. **Environmental Studies**: Comparing measurements from two different locations or times.

### Connections to Other Topics

- **Wilcoxon Signed-Rank Test**: Unlike the Mann–Whitney U test, which is applied to independent samples, the Wilcoxon signed-rank test is applied to matched or dependent samples.
- **Nonparametric Tests**: The Mann–Whitney U test is part of a family of nonparametric tests, which do not assume a specific distribution for the data.
- **Effect Sizes**: The test can be associated with measures of effect size, such as common language effect size or rank-biserial correlation.

### Obsidian Links

- [[Wilcoxon Signed-Rank Test]]
- [[Nonparametric Tests]]
- [[Hypothesis Testing]]
- [[Mathematical statistics]]