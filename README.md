# SARSA Reinforcement Learning on CliffWalking-v1

This project implements the **SARSA (State-Action-Reward-State-Action)** Reinforcement Learning algorithm using the Gymnasium `CliffWalking-v1` environment.

The agent learns an optimal navigation policy using:

* Q-table learning
* Epsilon-greedy exploration
* Temporal Difference (TD) learning
* On-policy reinforcement learning

# Environment

The environment used in this project is:

* CliffWalking-v1 from Gymnasium

The objective is:

* Reach the goal state
* Avoid falling into the cliff
* Minimize total negative reward

# Reinforcement Learning Concepts Used

## SARSA Update Rule

Where:

* (Q(s,a)) = current Q-value
* (\alpha) = learning rate
* (\gamma) = discount factor
* (r) = reward
* (Q(s',a')) = future Q-value estimate

# Epsilon-Greedy Policy

The agent balances:

* exploration
* exploitation

using epsilon-greedy action selection.


# Installation

Install dependencies:

```bash
pip install -r requirements.txt
```

# Requirements

```txt
numpy
gymnasium
pygame
matplotlib
```

# Running the Project

Run the Jupyter notebook:

```bash
jupyter notebook
```

Open:

```text
SARSA.ipynb
```

# Results

The SARSA agent gradually learns a safer path around the cliff through repeated interaction with the environment.

The project demonstrates:

* Temporal Difference Learning
* On-policy RL behavior
* Q-table updates
* Exploration vs exploitation tradeoff

# Future Improvements

* Add reward visualization graphs
* Compare SARSA vs Q-Learning
* Implement Deep SARSA using Neural Networks
* Add policy visualization

# Technologies Used

* Python
* NumPy
* Gymnasium
* Reinforcement Learning

# References

* Sutton & Barto — Reinforcement Learning: An Introduction
* Gymnasium Documentation
* David Silver RL Course
