The Neyman-Pearson Lemma is a fundamental theorem in statistical hypothesis testing, introduced by Jerzy Neyman and Egon Pearson in 1933. It is part of the Neyman-Pearson theory of statistical testing, which introduced concepts like errors of the second kind, power function, and inductive behavior.

## Statement

Consider a test with hypotheses H0:θ=θ0 and H1:θ=θ1​, where the probability density function (or probability mass function) is ρ(x∣θi) for i=0,1.

The Neyman-Pearson Lemma states:

- **Existence**: If a hypothesis test satisfies a specific condition, then it is a uniformly most powerful (UMP) test in the set of level αα tests.
- **Uniqueness**: If there exists a hypothesis test that satisfies the condition, with η>0η>0, then every UMP test in the set of level αα tests satisfies the condition with the same ηη.

The lemma extends to settings involving composite hypotheses with monotone likelihood ratios through the Karlin-Rubin theorem.

## Example

Consider a random sample from a normal distribution with known mean and testing for H0:σ2=σ02H0​:σ2=σ02​ against H1:σ2=σ12​. The likelihood ratio can be computed, and the most powerful test of this hypothesis for this data will depend only on the sum of squared differences from the mean. The rejection threshold depends on the significance level of the test, and the test statistic can be shown to be a scaled Chi-square distributed random variable.

## Applications

- **Economics**: A variant of the Neyman–Pearson lemma has found application in the economics of land value.
- **Electrical Engineering**: Useful in radar systems, digital communication systems, and signal processing systems.
- **Particle Physics**: Applied to the construction of analysis-specific likelihood-ratios, used to test for signatures of new physics against the nominal Standard Model prediction.

## Discovery of the Lemma

Neyman wrote about the discovery of the lemma, describing how it took half a decade of combined effort with Pearson to formulate the problem. The solution came to him in a flash one evening, and he realized that they were faced with a particular problem of the calculus of variation.

## Connections to Other Topics

- [[Hypothesis Testing]]: The lemma is a foundational concept in Hypothesis Testing.
- [[Type I Error]]: Related to the probability of making a Type I Error.
- [[Type II Error]]: Related to the probability of making a Type II Error.
- [[Mathematical statistics]]