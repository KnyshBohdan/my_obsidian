A Probability Measure is a real-valued function defined on a set of events in a probability space that satisfies measure properties such as countable additivity. It generalizes the concept of probability distributions and must assign value 1 to the entire probability space.

## Definition

A Probability Measure is a mapping that satisfies the following requirements:

1. **Value Range**: It must return results in the interval $[0,1]$, returning 0 for the empty set and 1 for the entire space.
2. **Countable Additivity**: It must satisfy the property that for all countable collections E1,E2,… of pairwise disjoint sets:
    
    $$\mu(\bigcup_{i \in N} E_i) = \sum_{i \in N} \mu (E_i)$$
    
3. **Conditional Probability**: The conditional probability based on the intersection of events is defined as:
    
    $$\mu (B | A) = \frac{\mu (A \cup B)}{\mu (A)}$$
    
    provided that μ(A)) is not zero.

## Example

Given three elements 1, 2, and 3 with probabilities 1/4,1/4, and 1/2, the value assigned to {1,3} is 1/4+1/2=3/4.

## Applications

Probability measures have applications in diverse fields, including:

- **Physics**: Used in statistical physics, although not all measures in physics are probability measures.
- **Finance**: Market measures assign probabilities to financial market spaces based on actual market movements, such as in the pricing of financial derivatives.
- **Biology**: Used in mathematical biology, such as in comparative sequence analysis for the likelihood that a variant may be permissible for an amino acid in a sequence.

## Distinctions

Probability measures are distinct from fuzzy measures, where there is no requirement that the values sum up to 1, and the additive property is replaced by an order relation based on set inclusion.

## Connections to Other Topics
[[Probability Spaces]]
- [[Probability Theory]]: Probability Measure is a foundational concept in Probability Theory.
- [[Statistical Physics]]: It is used in the concept of systems in statistical mechanics.
- [[Mathematical Finance]]: It is of interest in mathematical finance, such as in risk-neutral measures.
- [[Mathematical statistics]]