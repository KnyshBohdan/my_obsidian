Bayes' Theorem, named after Thomas Bayes, is a mathematical formula used to update the probability for a hypothesis H given new evidence E. It's a cornerstone of Bayesian statistics and has wide-ranging applications in various fields, including medicine, finance, and machine learning.

## Mathematical Statement

The theorem is stated mathematically as:

$$P(A|B) = \frac{P(B|A) P(A)}{P(B)}$$

Where:

- A and B are events.
- P(B)≠0.
- P(A∣B) is the conditional probability of A given B.
- P(B∣A)is the conditional probability of B given A.
- P(A) and P(B) are the probabilities of observing A and B respectively without any given conditions; they are known as the prior probability and marginal probability.

## Interpretation

- **Prior Probability**: P(A)represents the initial belief about A before taking into account the new evidence B.
- **Likelihood**: P(B∣A) represents how likely the evidence B is, assuming that A is true.
- **Marginal Likelihood**: P(B) represents the total probability of observing the evidence B.
- **Posterior Probability**: P(A∣B) represents the updated belief about A after taking into account the new evidence B.

## Applications

### Drug Testing

For example, in drug testing, Bayes' theorem can be used to calculate the probability that a person who tests positive is really a drug user, taking into account the sensitivity and specificity of the test, as well as the prevalence of drug use in the population.

### Recreational Mathematics

Bayes' theorem provides a solution method for popular puzzles like the Three Prisoners problem, the Monty Hall problem, and the Two Envelopes problem.

## History

Bayes' theorem was named after the Reverend Thomas Bayes, who used conditional probability to provide an algorithm for calculating limits on an unknown parameter. Independently of Bayes, Pierre-Simon Laplace used conditional probability to formulate the relation of an updated posterior probability from a prior probability, given evidence.

## Connections to Other Topics
[[Probability Spaces]]
- [[Probability Theory]]: Bayes' Theorem is a foundational concept in Probability Theory.
- [[Conditional Probability]]: It is an extension of the concept of conditional probability.
- [[Law of Total Probability]]: It is related to the law of total probability.