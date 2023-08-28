Marginal Distribution is a probability distribution for a subset of the variables in a multivariate distribution. It provides the probabilities for a single variable without reference to the values of the other variables.

## Definition

Given a joint probability distribution for two random variables X and Y, the marginal distribution of X is obtained by summing or integrating over all possible values of Y:

### For Discrete Random Variables

$$P(X=x)=\sum_yP(X=x,Y=y)$$

### For Continuous Random Variables

$$f_X(x) = \int f_{X, Y}(x, y)dy$$

where fX,Y(x,y) is the joint probability density function of X and Y.

## Interpretation

The marginal distribution of a variable provides a summary of the probabilities for that variable, ignoring the relationships with other variables. It's useful for understanding the behavior of a single variable within a multivariate system.

## Applications

- **Statistical Modeling**: Marginal distributions are used in statistical modeling to analyze the behavior of individual variables within a multivariate model.
- **Machine Learning**: In machine learning, marginal distributions are used in algorithms that deal with multivariate data, such as clustering and classification.

## Connections to Other Topics

- [[Joint Distribution]]: Marginal Distribution is derived from the joint distribution of multiple random variables.
- [[Probability Theory]]: Marginal Distribution is a core concept within Probability Theory, particularly in the context of multivariate distributions.
- [[Random Variable]]: Marginal Distribution describes the distribution of a single random variable within a multivariate system.
- [[Mathematical statistics]]: This concept plays a significant role in Mathematical Statistics, especially in multivariate analysis.
- [[Random Variable]]