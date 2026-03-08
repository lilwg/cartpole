# CartPole

Balance a pole on a cart — play it yourself or train a reinforcement learning agent to do it automatically.

**[Play at cartpole.lilwg.com](https://cartpole.lilwg.com)**

## Modes

- **Human** — use left / right arrow keys to balance the pole yourself
- **AI Agent** — pick an algorithm, hit Train Agent, and watch it learn over hundreds of episodes

## Algorithms

| Algorithm | Type |
|-----------|------|
| **Q-Learning** | Tabular |
| **REINFORCE** | Policy gradient with neural network |
| **DQN** | Deep Q-Network with replay buffer |
| **PPO** | Proximal Policy Optimization |

The training chart updates live and you can click any point on it to replay the agent from that snapshot. A neural network visualisation shows activations in real time for network-based agents.

## Stack

Pure vanilla JavaScript, no dependencies. All RL algorithms and neural network inference run directly in the browser.
