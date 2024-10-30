# NeuroChess

NeuroChess is an AI-powered chess engine that utilizes reinforcement learning and Monte Carlo Tree Search (MCTS) to learn and improve its gameplay by playing against itself. The engine is built using Python and TensorFlow, leveraging the capabilities of deep learning to evaluate positions and generate optimal moves.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Algorithm Overview](#algorithm-overview)
- [Training](#training)
- [Using the Neural Network in Arena Chess](#using-the-neural-network-in-arena-chess)
- [Testing](#testing)
- [Acknowledgments](#acknowledgments)


## Features

- Reinforcement Learning using TensorFlow and pytorch
- Monte Carlo Tree Search for optimal move generation
- Self-play mechanism to improve performance over time
- Integration with the `python-chess` library for chess logic
- Adjustable parameters for training and gameplay settings

## Installation

To set up the NeuroChess project, follow these steps:

1. Clone the repository:
  - git clone https://github.com/yourusername/neurochess.git
  - cd neurochess
2. Install the required dependencies:
  - pip install -r requirements.txt

## Algorithm Overview
- [MCTS Algorithm Video](https://youtu.be/hmQogtp6-fs?si=50SB4yCgE_itD7x9) - A video explaining the principles of MCTS.
- [MCTS Algorithm Overview](https://www.geeksforgeeks.org/ml-monte-carlo-tree-search-mcts/) - A detailed article about MCTS.
- [Reinforcement Learning Explanation](https://www.geeksforgeeks.org/what-is-reinforcement-learning/) - An overview of reinforcement learning concepts.

## Training
Training involves running the self-play mechanism where the engine plays against itself to collect data. This data is then used to update the neural network.

## Usage
Once you have trained the model and exported the weights, you can integrate the neural network with Arena Chess for testing against other engines or human players. Follow these steps to set it up:
  1. Export the trained model weights.
  2. Configure Arena Chess to use the neural network as an engine by specifying the path to the weights.
  3. Launch Arena Chess and select your neural network engine for gameplay.

## Testing
After training, you can test the performance of the trained model against standard chess engines or human players to evaluate its strength and improvements.

## Acknowledgements
Special thanks to the following resources:
- [AlphaZero](https://deepmind.google/discover/blog/alphazero-shedding-new-light-on-chess-shogi-and-go/) - Google's AI Engine For Various Board Games like GO,Shogi and Chess.
