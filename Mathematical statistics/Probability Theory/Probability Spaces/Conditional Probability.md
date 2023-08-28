Conditional Probability is a measure of the probability of an event occurring, given that another event (by assumption, presumption, assertion, or evidence) has already occurred. It plays a crucial role in various statistical analyses and has applications in diverse fields.

## Definition

The conditional probability of an event AA given an event BB is usually written as P(A∣B). It can be understood as the fraction of probability BB that intersects with AA, or the ratio of the probabilities of both events happening to the "given" one happening:

$$P(A|B) = \frac{P(A|B)}{P(B)}$$

### Example

The probability that any given person has a cough on any given day may be only 5%. But if we know or assume that the person is sick, then they are much more likely to be coughing. For example, the conditional probability that someone unwell (sick) is coughing might be 75%, in which case we would have that P(Cough)=5% and P(Cough|Sick)=75%.

## Independence

If P(A∣B)=P(A), then events A and B are said to be independent. In such a case, knowledge about either event does not alter the likelihood of each other.

## Kolmogorov Definition

Given two events from the sigma-field of a probability space, with the probability of B being greater than zero, the conditional probability of A given B is the probability of A occurring if B has or is assumed to have happened.

## Conditioning on an Event of Probability Zero

If P(B)=0, then the conditional probability is undefined. Special considerations must be made when dealing with continuous random variables or events with probability zero.

## As an Axiom of Probability

Some authors prefer to introduce conditional probability as an axiom of probability:

$$P(A \cap B) = P(A | B)P(B)$$

## Conditional Probability Distribution

For continuous random variables, the conditional probability distribution can be defined using limits and integral rules.

## Jeffrey Conditionalization

Jeffrey conditionalization is a special case of partial conditional probability, in which the condition events must form a partition.

## Example with Dice

Suppose that somebody secretly rolls two fair six-sided dice, and we wish to compute the probability that the face-up value of the first one is 2, given the information that their sum is no greater than 5.

## Connections to Other Topics
[[Probability Spaces]]
- [[Probability Theory]]: Conditional Probability is a foundational concept in Probability Theory.
- [[Independence]]: It contrasts with the concept of independence.
- [[Law of Total Probability]]: It is related to the law of total probability.
- [[Bayes' Theorem]]: It is essential in the application of Bayes' theorem.