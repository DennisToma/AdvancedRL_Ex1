# Blackjack Q-Learning Project

## Project Description

This project implements a Q-learning algorithm to train an agent to play the game of Blackjack optimally. The agent learns through interaction with the environment, improving its strategy over time by updating a Q-table based on the rewards received from different actions.

## Features

- **Environment**: Utilizes the `gymnasium` library to simulate the Blackjack environment.
- **Q-Learning Algorithm**: Implements a Q-learning algorithm with adjustable hyperparameters such as learning rate, discount factor, and exploration rate.
- **Performance Tracking**: Tracks the mean return over episodes to monitor the learning progress.
- **Visualization**: Includes a plot of the mean return over time to visualize the agent's learning process.

## Installation

To run this project, you need to have Python installed along with the following packages:

- `gymnasium`
- `numpy`
- `matplotlib`

You can install these packages using pip:

```bash
pip install gymnasium numpy matplotlib
```

## Usage

1. Clone the repository.
2. Open the `black_jack_rl.ipynb` notebook.
3. Run the cells to train the agent and visualize the results.

## Results

The learning process is visualized in the `black_jack_rl_graph.png` image, which shows the mean return over time as the agent learns to play Blackjack.

![Learning Process](black_jack_rl_graph.png)

## License

This project is licensed under the MIT License.

## Acknowledgments

- The `gymnasium` library for providing the Blackjack environment.
- The Q-learning algorithm for reinforcement learning.