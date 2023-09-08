Blackwell's Approachability Theorem addresses the challenges in multivariate payoff functions in game theory. Unlike scalar-valued games where the minmax theory applies straightforwardly, vector-valued games require a nuanced approach. The theorem focuses on directing the payoff vector towards a convex set S⊆$R^d$.

#### Mathematical Formulation

The payoff function $r: \Delta^n \times \Delta^m \to R^d$ is assumed to be biaffine. The theorem states that if for every half-space H containing S, there exists a strategy pp such that $r(p,q)∈H$ for all q, then there exists an adaptive strategy ptpt​ that makes the average payoff vector approach S as T→∞.

#### Algorithmic Strategy

The lecture outlines an adaptive strategy algorithm. It computes an average payoff $\overline{r}_t$ at each time t. If  $\overline{r}_t$  is not in S, it projects  $\overline{r}_t$ ​ onto S and selects a half-space Ht+1​ containing S such that ​$r(p_{t + 1}, q) \in H_{t + 1}$ for all q.

#### Applications

The theorem has applications in online learning settings. It can be used to minimize regret when choosing weights w1,w2,… in the face of observed loss vectors.

### Key Insights

1. **Multivariate Complexity**: The theorem extends the minmax theory to multivariate settings, addressing the complexity of optimizing a vector.
    
2. **Convex Set Targeting**: The goal is not to maximize or minimize but to direct the payoff vector into a convex set.
    
3. **Adaptive Strategy**: The theorem provides a constructive proof, offering an algorithmic way to achieve the approachability.
    
4. **Online Learning**: The theorem can be applied to solve problems in online learning, providing a way to minimize regret.
    
5. **Duality**: The theorem explores a form of duality between half-spaces and convex sets, which is crucial for its applications.

### Connection to Other Topics

- **[[Game Theory]]**: BAT is a specialized concept within game theory that extends the classical minmax theory to vector-valued games. Understanding basic game theory concepts like Nash Equilibrium and Zero-Sum Games can provide a foundational understanding for BAT.
    
- **[[Convex Optimization]]**: The theorem involves directing a payoff vector into a convex set, which is a key concept in convex optimization. Understanding convex functions and optimization algorithms can provide deeper insights into the theorem.
    
- **[[Online Learning]]**: BAT has direct applications in online learning algorithms, particularly in regret minimization. Understanding the basics of online learning can help in applying the theorem practically.
    
- **[[Linear Algebra]]**: The theorem involves vector spaces and linear transformations, making a good understanding of linear algebra beneficial for grasping the mathematical intricacies of BAT.
    
- **[[Probability Theory]]**: The adaptive strategy in BAT involves probabilistic elements, making it essential to understand basic probability theory for a full comprehension of the theorem.
    
- **[[Decision Theory]]**: BAT can be viewed as a decision-making framework under uncertainty, making it relevant to decision theory. Understanding utility functions and decision-making under uncertainty can provide a broader context for the theorem.
    
- **[[Computational Complexity]]**: The algorithmic aspect of BAT involves computational considerations. Understanding computational complexity can help in assessing the efficiency of algorithms derived from BAT.