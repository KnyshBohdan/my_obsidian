### Definition

Fisher's Exact Test is a statistical significance test used to analyze contingency tables, particularly 2 × 2 tables. Unlike approximations that rely on large sample sizes, Fisher's Exact Test calculates the exact significance of the deviation from a null hypothesis (e.g., p-value), making it valid for all sample sizes.

### Key Concepts

1. **Null Hypothesis**: The test assumes no association between the two classifications in the contingency table.
2. **Exact Test**: The test calculates the exact p-value without relying on approximations.
3. **Hypergeometric Distribution**: Under the null hypothesis of independence, the numbers in the cells of the table follow a hypergeometric distribution.
4. **Two-tailed Test**: The test can be two-tailed, considering tables that are equally extreme but in opposite directions.

### Example

Consider a sample of teenagers divided into male and female, and those who are and are not studying for a statistics exam. The data might look like:

|   |   |   |   |
|---|---|---|---|
||Men|Women|Row total|
|Studying|1,00|9,00|10,00|
|Not-studying|11,00|3,00|14,00|
|Column total|12,00|12,00|24,00|

The question is whether the distribution of studying teenagers is significantly uneven between men and women. The Fisher's Exact Test can be applied to this data, and the p-value can be calculated using the hypergeometric distribution:

$$p = \frac{(a + b)! (c + d)! (a + c)! (b + d)!}{a!b!c!d!n!}$$

### Applications

1. **Categorical Data Analysis**: Useful for analyzing categorical data resulting from classifying objects in two different ways.
2. **Overlap Analysis**: Can be used to quantify the overlap between two sets, such as in enrichment analyses in statistical genetics.
3. **Small Sample Sizes**: Particularly useful when sample sizes are small or data are very unequally distributed among the cells of the table.

### Connections to Other Topics

- **Chi-Squared Test**: With large samples, a chi-squared test can be used, but Fisher's Exact Test is preferred when the chi-squared approximation is inadequate.
- **G-Test**: Another alternative for large samples.
- **Barnard's Test**: A related test that relaxes constraints on one set of marginal totals.

### Obsidian Links

- [[Chi-Squared Test]]
- [[G-Test]]
- [[Barnard's Test]]
- [[Hypergeometric Distribution]]