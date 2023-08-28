Marginal Probability refers to the probability distribution of a subset of random variables, giving the probabilities of various values of the variables in the subset without considering the values of the other variables. It contrasts with conditional distribution, which gives probabilities contingent upon the values of other variables.

## Definition

### Marginal Probability Mass Function

Given a known joint distribution of two discrete random variables, say XX and YY, the marginal distribution of either variable can be calculated by summing the joint probability distribution over all values of the other variable:

$$p_X(x_i) = \sum_{j} p(x_i, y_j)$$

$$p_Y(y_i) = \sum_{i} p(x_i, y_j)$$
### Marginal Probability Density Function

For continuous random variables, the marginal probability density function can be obtained by integrating the joint distribution over the other variable:

$$f_X(x) = \int_c^d f(x, y) dy$$

$$f_Y (y) = \int_{a}^{b} f(x, y) dx$$

## Example

Suppose there is data from a classroom of 200 students on the amount of time studied and the percentage of correct answers. Assuming that the variables are discrete, the joint distribution can be described, and the marginal probability can be used to determine specific probabilities, such as the probability that a student who studied 60 minutes or more obtains a score of 20 or below.

## Real-world Example

Consider the probability that a pedestrian will be hit by a car while crossing the road at a pedestrian crossing without paying attention to the traffic light. The marginal probability P(H=Hit) can be found by summing P(H∣L) for all possible values of L, with each value of L weighted by its probability of occurring.

## Connections to Other Topics
[[Probability Spaces]]
- [[Probability Theory]]: Marginal Probability is a foundational concept in Probability Theory.
- [[Joint Distribution]]: It is derived from the joint distribution of the variables.
- [[Conditional Distribution]]: It contrasts with conditional distribution, which considers the values of other variables.
- [[Continuous Random Variables]]: The concept extends to continuous random variables as well.