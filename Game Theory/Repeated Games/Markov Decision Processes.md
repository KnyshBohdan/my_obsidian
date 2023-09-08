Markov Decision Processes provide a mathematical framework for modeling decision-making in situations where outcomes are partly random and partly under the control of a decision-maker. MDPs are widely used in optimization, artificial intelligence, economics, and operations research, among other fields.

## Definition

An MDP is defined by a tuple (S,A,P,R), where:

- S is a finite set of states.
- A is a finite set of actions.
- P is the state transition probability, P(s′∣s,a), representing the probability of transitioning from state ss to state s′ under action aa.
- R is the reward function, R(s,a,s′), which gives the immediate reward received after transitioning from state ss to state s′, taking action aa.

## Key Concepts

- **Policy**: A policy π defines the mapping from states to actions, specifying the action to take in each state.
    
- **Value Function**: The value function $V^\pi (s)$ gives the expected return when starting in state s and following policy π.
    
- **Bellman Equation**: The value function satisfies the Bellman equation, which can be used to find the optimal policy.
    

## Applications

- **Robotics**: For path planning and navigation.
    
- **Finance**: For portfolio optimization.
    
- **Healthcare**: For treatment policies.
    

## Connection to Other Topics

- **[[Game Theory]]**: MDPs can be generalized to multi-agent settings, known as stochastic games or Markov games.
    
- **[[Optimization]]**: MDPs are a form of dynamic programming problem.
    
- **[[Artificial Intelligence]]**: MDPs are foundational in reinforcement learning.
    
- **[[Operations Research]]**: Used in inventory management, queuing systems, and other optimization problems.