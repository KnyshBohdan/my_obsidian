Q-Learning is a model-free reinforcement learning algorithm used to find the optimal action-selection policy for a given finite Markov decision process. It is particularly powerful because it can handle problems with stochastic transitions and rewards without requiring adaptations.

## Definition

Q-Learning is designed to learn the value of an action in a particular state. It does not require a model of the environment, making it "model-free." The algorithm computes the expected rewards for an action taken in a given state, denoted as Q(s,a).

## Algorithm

The core of Q-Learning is the Q-table, a table of states by actions initialized to zero. Each cell in the table is updated through training using the following equation:

$Q(s,a)=Q(s,a)+α×(r+γ×max⁡(Q(s′,a′))−Q(s,a))$

Where:

- α is the learning rate
- γ is the discount factor
- r is the actual reward received for that action
- s′ refers to the next state
- max⁡(Q(s′,a′)) is the highest expected reward for all possible actions a′ in state s′

## Applications

- **Game Theory**: Used to develop optimal strategies in games.
- **Robotics**: For navigation and task completion.
- **Finance**: For optimizing trading strategies.

## Key Concepts

- **State**: The current situation the agent evaluates.
- **Action**: What the agent can do.
- **Reward**: A numerical score that the agent aims to maximize.
- **Exploration vs. Exploitation**: The agent must balance between trying new actions and sticking with known, rewarding actions.

## Challenges

- **Sparse Rewards**: In many real-world scenarios, rewards are infrequent.
- **Computational Complexity**: The Q-table can become very large in complex environments.

## Connection to Other Topics

- **[[Reinforcement Learning]]**: Q-Learning is a specialized algorithm within RL.
- **[[Markov Decision Process]]**: The mathematical framework that Q-Learning operates within.
- **[[Temporal Difference Learning]]**: Q-Learning is often considered a form of Temporal Difference Learning.
- [[Machine Learning]]
- [[Artificial Intelligence]]