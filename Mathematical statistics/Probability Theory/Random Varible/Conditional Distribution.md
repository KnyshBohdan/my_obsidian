In probability theory and statistics, the conditional distribution of a random variable given another is the probability distribution when one variable is known to be a particular value. It contrasts with the marginal distribution of a random variable, which is its distribution without reference to the value of the other variable.

## Definition

### Conditional Discrete Distributions

For discrete random variables, the conditional probability mass function of X=x can be written as:

$$p_{Y|X}(y|x) = \frac{P(\{X=x\}\cap \{ Y = y\})}{P(X=x)}$$

### Conditional Continuous Distributions

Similarly, for continuous random variables, the conditional distribution given the occurrence of the value can be written as:

$$f_{Y|X}(y|x) = \frac{f_{X, Y}(x, y)}{f_{X}(x)}$$

## Examples

### Roll of a Fair Die

Consider the roll of a fair die, and let X=1 if the number is even (i.e., 2, 4, or 6) and X=0 otherwise. Let Y=1 if the number is prime (i.e., 2, 3, or 5) and Y=0 otherwise. Then the unconditional probability that X=1 is 1/2, whereas the probability that X=1 conditional on Y=1 is 1/3.

## Properties

- **Relation to Independence**: Random variables are independent if and only if the conditional distribution of one is, for all possible realizations of the other, equal to the unconditional distribution of that variable.
- **Measure-theoretic Formulation**: The conditional probability can be expressed using the Radon-Nikodym theorem, leading to a measurable random variable that represents the conditional probability.
- **Special Cases**: Specific formulations exist for different sigma algebras and random variables, including real-valued random variables.

## Connections to Other Topics

- [[Joint Distribution]]: Conditional distribution is derived from the joint distribution of the variables.
- [[Marginal Distribution]]: It contrasts with the marginal distribution, which considers the distribution of a variable without reference to others.
- [[Probability Theory]]: Conditional distribution is a core concept within Probability Theory, providing insight into the relationship between variables given certain conditions.
- [[Mathematical statistics]]: Conditional distribution plays a significant role in Mathematical Statistics, especially in statistical modeling and analysis.
- [[Random Variable]]