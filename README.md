# Deep Reinforcement Learning From Scratch

Implementations of core deep reinforcement learning algorithms from first principles in PyTorch, developed to build a rigorous understanding of modern RL methods and their foundations for model-based RL and world models.

## Overview

This repository documents a progression from PyTorch and neural network fundamentals through value-based and policy based reinforcement learning.

The emphasis is on implementing core algorithms directly rather than relying on high-level RL libraries, with experiments used to investigate training behaviour, stability and design choices.

## Implementations

### Foundations
 - PyTorch tensor operations and autograd.
 - Neural Networks and optimisation
 - Representation Learning 

### Reinforcement Learning
 - Markov Decision Process
 - Value Iteration
 - Q-Learning
 - Deep Q-Networks (DQN)
 - Reinforce
 - Actor-Critic
 - Generalised Advantage Estimate (GAE)
 - Proximal Policy Optimisation (PPO)

## Repository Structure
deep-rl-from-scratch/
├── foundations/
├── environments/
├── agents/
│   ├── dqn/
│   ├── reinforce/
│   └── ppo/
├── networks/
├── experiments/
├── tests/
└── README.md

## Experiments

Experiments evaluate factors including:

 - learning stability
 - sample efficiency
 - hyperparameter sensitivity
 - exploration strategies
 - network architecture
 - reproducibility across random seeds

 - I'll add results and learning curves will be added as implementations are completed.

## Roadmap

- [ ] PyTorch foundations
- [ ] Tabular Q-Learning
- [ ] DQN
- [ ] REINFORCE
- [ ] Actor-Critic
- [ ] GAE
- [ ] PPO
- [ ] Continuous control
- [ ] Algorithm benchmarking

## Technologies

- Python
- PyTorch
- Gymnasium
- NumPy
- Matplotlib

## Motivation

This project builds the reinforcement-learning foundation for subsequent work
on model-based reinforcement learning, learned world models, and hybrid
quantum-classical RL architectures.

## References

Key papers and learning resources used throughout the project will be
documented here.

## License

MIT License
