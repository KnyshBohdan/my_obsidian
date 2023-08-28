Covariance is a measure of the joint variability of two random variables. It indicates the degree to which two random variables change together. If the greater values of one variable correspond with the greater values of the other variable, the covariance is positive. Conversely, if the greater values of one variable correspond to the lesser values of the other, the covariance is negative.

## Definition

### For Real-Valued Random Variables

For two jointly distributed real-valued random variables X and Y with finite second moments, the covariance is defined as:

$$cov(X, Y) = E[(X - E[X])(Y - E[X])] = E[XY] - E[X]E[Y]$$
### For Complex Random Variables

For complex random variables Z and W, the covariance is defined as:

$$cov(Z, W) = E[(Z - E[Z])\overline{(W - E[W])}] = E [Z\bar{W}] - E[Z]E[\bar{W}]$$
### For Discrete Random Variables

For discrete random variables, the covariance can be expressed as:

$$cov(X, Y) = \frac{1}{n}\sum_{i=1}^{n}(x_i - E(X))(y_i - E(Y))$$

## Geometric Interpretation

The sign of the covariance shows the tendency in the linear relationship between the variables. The magnitude of the covariance is the geometric mean of the variances that are in common for the two random variables.

## Properties

- **Covariance with Itself**: cov⁡(X,X)=var⁡(X)
- **Covariance of Linear Combinations**: Various properties related to linear combinations of random variables.
- **Uncorrelatedness and Independence**: Random variables whose covariance is zero are called uncorrelated. If they are independent, their covariance is zero, but the converse is not generally true.

## Examples

- **Geometric Interpretation**: The covariance can be visualized as the sum of the volumes of cuboids in specific quadrants.
- **Special Cases**: Specific examples can be constructed using independent random variables and constants.

## Connections to Other Topics

- [[Variance]]: Covariance with itself is a special case of covariance, known as variance.
- [[Random Variable]]: Covariance is a property of two random variables, describing their joint variability.
- [[Probability Theory]]: Covariance is a core concept within Probability Theory, providing insight into the relationship between two variables.
- [[Mathematical statistics]]: Covariance plays a significant role in Mathematical Statistics, especially in statistical modeling and analysis.