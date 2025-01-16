# Reinforcement-Learning

The primary goal of this project is to gain hands-on experience in defining and solving reinforcement learning (RL) environments.

Overview

Part 1: Environment Definition (Grid-World as an MDP)
In this section, we define a grid-world RL environment modeled as a Markov Decision Process (MDP). The key components include:

States: Representation of the environment's possible configurations.
Actions: The set of moves available to the agent.
Rewards: The numerical feedback based on the agent's actions and transitions.
Other Parameters: Additional constraints or features to define the environment.


Part 2: Solving with SARSA
We implement the SARSA (State-Action-Reward-State-Action) algorithm and apply it to the grid-world environment created in Part 1.

About SARSA:
An on-policy reinforcement learning algorithm.
The agent learns Q-values by interacting with the environment and observing transitions: (state, action, reward, next_state, next_action).
Balances exploration (discovering new actions) and exploitation (using learned knowledge).


Part 3: Solving with Q-Learning
We use the Q-learning algorithm to solve the same environment from Part 1.

About Q-Learning:
An off-policy RL algorithm.
Updates the Q-value of the current state-action pair based on the maximum Q-value of the next state.
Focuses on finding an optimal policy by maximizing future rewards.
Features
Comprehensive implementation of MDP-based RL environments.
Comparison of SARSA and Q-learning algorithms.
Hands-on exploration of exploration-exploitation trade-offs.
An off-policy RL algorithm.
Updates the Q-value of the current state-action pair based on the maximum Q-value of the next state.
Focuses on finding an optimal policy by maximizing future rewards.
Features
Comprehensive implementation of MDP-based RL environments.
Comparison of SARSA and Q-learning algorithms.
Hands-on exploration of exploration-exploitation trade-offs.
