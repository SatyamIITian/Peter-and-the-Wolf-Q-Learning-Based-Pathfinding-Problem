# Peter-and-the-Wolf-Q-Learning-Based-Pathfinding-Problem
Q-learning-based solution to a pathfinding problem inspired by the "Peter and the Wolf" fairy tale. The goal is for Peter to navigate a grid environment, collecting apples while avoiding obstacles like wolves and water. 

## 📁 Files Included

- `2411AI44_RL_ASSGNMENT_1_CODE.ipynb`: Jupyter Notebook containing Python implementation of various RL algorithms.

## 🧠 Problem Statement

To explore and compare the performance of different Reinforcement Learning strategies—Value Iteration, Policy Iteration, and Q-Learning—on a stochastic environment (`FrozenLake-v1`), with the goal of maximizing the agent’s success rate in reaching the goal without falling into holes.

## 🔧 Algorithms Implemented

- **Value Iteration**: A model-based planning algorithm using Bellman Optimality.
- **Policy Iteration**: An iterative policy improvement technique.
- **Q-Learning**: A model-free algorithm using exploration-exploitation tradeoff.

## 📊 Evaluation Metrics

- Number of episodes to convergence
- Average reward over episodes
- Policy stability
- Time efficiency of each algorithm

## 🏁 Environment Used

- `FrozenLake-v1` from OpenAI Gym
- `is_slippery=True` to simulate a non-deterministic environment

## 📌 Requirements

To run the notebook, install the following Python packages:

```bash
pip install numpy matplotlib gym
