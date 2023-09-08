Stochastic Games, also known as Markov games, are a type of repeated game with probabilistic transitions. Introduced by Lloyd Shapley in the early 1950s, these games are played in a sequence of stages where the game state changes randomly based on the actions chosen by the players.

## Definition

A stochastic game is defined by:

- A finite set of players I
- A state space M
- An action set Si for each player i
- A transition probability PP from M×Sto M
- A payoff function g from M×S to $R^I$

The game starts at an initial state $m_1$​. At each stage tt, players observe the current state mtmt​, choose actions stisti​, and then transition to a new state $m_{t+1}$ based on the probability $P(⋅∣m_t,s_t)$.

## Key Concepts

- **Discounted Game**: The total payoff to a player is often the discounted sum of stage payoffs.
    
- **Equilibrium Value**: In many cases, there exists an equilibrium value of the probability of "good" runs, but optimal strategies for both players may not exist.
    
- **Markov Strategy**: A strategy is called a Markov strategy if the behavior dictated is not time-dependent.
    

## Applications

- **Operations Research**: Used for modeling and analysis of discrete systems.
    
- **Economics**: Applied in market dynamics where future states are uncertain.
    
- **Computer Science**: Used in machine learning and artificial intelligence for decision-making under uncertainty.
    

## Connection to Other Topics

- **[[Markov Decision Processes]]**: Stochastic games generalize Markov decision processes to multiple interacting decision-makers.
    
- **[[Game Theory]]**: Stochastic games are a subfield of game theory, focusing on dynamic situations with probabilistic transitions.
    
- **[[Repeated Games]]**: Stochastic games can be viewed as an extension of repeated games with state transitions.
    
- **[[Non-cooperative Games]]**: Stochastic games often fall under the category of non-cooperative games where players act independently.