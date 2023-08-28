Joint Distribution refers to the probability distribution that describes the behavior of two or more random variables simultaneously. It provides a complete description of the statistical dependence between the variables.

## Definition

### Discrete Random Variables

For discrete random variables X and Y, the joint probability mass function is given by:

$$p_{X, Y}(x, y) = P(X = x \ and \ Y = y)$$

### Continuous Random Variables

For continuous random variables, the joint probability density function is given by:

$$f_{X, Y} = \frac{\partial ^2 F_{X, Y}(x, y)}{\partial x \partial y}$$

where FX,Y(x,y) is the joint cumulative distribution function.

## Examples

### Coin Flips

Consider the flip of two fair coins; let AA and BB be discrete random variables associated with the outcomes of the first and second coin flips respectively. The joint probability mass function becomes:

$$P(A, B) = 1/4 \ \ \ for \ \ \ A, B \in {0, 1}$$

### Draws from an Urn

If two urns contain twice as many red balls as blue balls, and one ball is randomly selected from each urn, the joint probability distribution can be represented in a table, with probabilities such as (2/3)(2/3)=4/9 for both red.

## Properties

### Independence

Two random variables are independent if and only if the joint cumulative distribution function satisfies:

$$F_{X, Y}(x, y) = F_X(x) F_Y(y)$$

## Connections to Other Topics

- [[Marginal Distribution]]: The joint distribution encodes the marginal distributions, i.e., the distributions of each of the individual random variables.
- [[Conditional Probability]]: It also encodes the conditional probability distributions, dealing with how the outputs of one random variable are distributed when given information on the others.
- [[Probability Theory]]: Joint Distribution is a core concept within Probability Theory, particularly in multivariate analysis.
- [[Random Variable]]: Joint Distribution describes the distribution of multiple random variables within a system.
- [[Mathematical statistics]]: This concept plays a significant role in Mathematical Statistics, especially in multivariate analysis.