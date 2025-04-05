# 🚀 Lunar Lander - Reinforcement Learning Project

This project implements a reinforcement learning agent to solve the **LunarLander-v2** environment using **OpenAI Gym**. The goal of the agent is to land a spacecraft safely on the moon's surface by learning optimal control policies through interactions with the environment.

## 📂 Project Structure

- `Lunar-Lander.ipynb`: The main Jupyter notebook containing code, training logic, and evaluation of the reinforcement learning agent.
- `README.md`: Project overview and setup instructions.

## 🧠 Approach

The agent uses a **Deep Q-Network (DQN)** algorithm to learn an optimal policy through experience replay and target network updates. Key features include:

- Neural network as a function approximator.
- Experience replay buffer for efficient learning.
- Target network to stabilize training.
- Epsilon-greedy strategy for exploration.

## 📦 Dependencies

To run this project, install the following Python libraries:

```bash
pip install gym
pip install matplotlib
pip install numpy
pip install torch
