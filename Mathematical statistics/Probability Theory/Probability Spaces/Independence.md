Independence is a core notion in probability theory, statistics, and the theory of stochastic processes. Two events or random variables are considered independent if the occurrence of one does not affect the probability of occurrence of the other.

## Definition

### For Events

Two events A and B are independent if and only if their joint probability equals the product of their probabilities:

$$P(A \cap B) = P(A)P(B)$$

This definition implies that the occurrence of AA does not affect the probability of BB, and vice versa.

### For Random Variables

Two random variables X and Y are independent if the realization of one does not affect the probability distribution of the other. The joint cumulative distribution function must satisfy:

$$F_{X, Y}(x, y) = F_X(x)F_Y(y) \ \ for \ all \ x, y$$

### More Than Two Events or Random Variables

- **Pairwise Independence**: Events are pairwise independent if any two events in the collection are independent of each other.
- **Mutual Independence**: Events are mutually independent if each event is independent of any combination of other events in the collection.

## Odds

Two events are independent if and only if the odds ratio of one is unity (1). This is equivalent to the conditional odds being equal to the unconditional odds.

## Log Probability and Information Content

Two events are independent if and only if the log probability of the joint event is the sum of the log probability of the individual events:

$$log(P(A \cap B)) = log(P(A)) + log(P(B))$$

## For Stochastic Processes

- **For One Stochastic Process**: Independence may be extended from random vectors to a stochastic process.
- **For Two Stochastic Processes**: Independence of two stochastic processes is a property between two stochastic processes defined on the same probability space.

## Connections to Other Topics
[[Probability Spaces]]
- [[Probability Theory]]: Independence is a foundational concept in Probability Theory.
- [[Joint Distribution]]: It relates to the joint distribution of variables.
- [[Conditional Probability]]: It contrasts with conditional probability, where the probability of one event depends on the occurrence of another.