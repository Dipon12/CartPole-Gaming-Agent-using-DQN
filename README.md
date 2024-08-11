# CartPole Gaming Agent using DQN
The project aims to create a reinforcement learning agent capable of mastering the CartPole game using the Deep Q-Network (DQN) algorithm.

<div align="center"><img src="https://github.com/user-attachments/assets/1e7eb842-f078-4dc2-a596-c3de96803724"></div>

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Files](#files)

# Overview

This project implements a reinforcement learning solution to the CartPole-v1 environment using a Deep Q-Network (DQN) algorithm. The CartPole-v1 environment is a standard benchmark in reinforcement learning where the objective is to control a cart moving along a one-dimensional track by applying forces to keep a pole balanced vertically. The agent receives a reward at each time step based on how well it keeps the pole balanced, and the episode ends if the pole falls beyond a certain angle or the cart moves too far from the center. For more information on the environment, visit [this page](https://gymnasium.farama.org/environments/classic_control/cart_pole/).

## Key Features

- Implementation of the DQN algorithm.
- Experience replay for efficient training.
- Target network to stabilize training. 

## Installation

To run the code in this repository, you need to have Python installed along with the following dependencies:

- PyTorch
- OpenAI Gym
- Numpy
- Matplotlib

You can install the required packages using `pip`:

```bash
pip install tensorflow gym numpy matplotlib
```

## Usage
The main implementation is provided in the Jupyter Notebook CartPole Gaming Agent using DQN.ipynb. You can run this notebook to train the DQN agent and visualize its performance.

### Steps to Run
1. Clone the repository:
```bash
git clone https://github.com/Dipon12/CartPole-Gaming-Agent-using-DQN.git
cd CartPole-Gaming-Agent-using-DQN
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```
3. Open the Jupyter Notebook and run the cells to train the agent:
```bash
jupyter notebook "CartPole Gaming Agent using DQN.ipynb"
```

## Results
After training, the DQN agent should be able to balance the pole for a significant number of time steps. The training progress and results are visualized in the notebook using plots of the reward over episodes.

## Files
- CartPole Gaming Agent using DQN.ipynb: The main Jupyter Notebook containing the implementation and training of the DQN agent.
- README.md: This file, providing an overview and instructions for the project.

