# 02 - Markov Decision Processes

This is a collection of resources for learning about Markov Decision Processes (MDPs). MDPs are a powerful tool for modeling sequential decision making problems. They are used in a wide variety of applications, including robotics, game theory, and reinforcement learning.


### Markov Property

A Markov process is a stochastic process that satisfies the Markov property. The Markov property states that the future is independent of the past given the present. In other words, the future is conditionally independent of the past given the present. The Markov property is a fundamental assumption in Markov decision processes.


### Markov Decision Process

A Markov decision process (MDP) is a Markov process that includes decisions. The decision maker chooses an action at each time step. The decision maker's goal is to maximize the expected value of the cumulative reward. The decision maker's goal is to find the optimal policy, which is a mapping from states to actions that maximizes the expected value of the cumulative reward.


### Bellman Equation

The modified Bellman equation from [bellman equation](../01-bellman-equation/README.md) will be used to solve the optimal control problem. The Bellman equation is

```
V*(s)= max[R(s,a)+ γ E{P(s'|s,a) V∗(s′)}]
```


where

> $P(s'|s,a)$ is the transition probability

from previous state $s$ to next state $s'$ given action $a$.

| 0.81 | 0.9  | 1    | 🟢    |
| ---- | ---- | ---- | ---- |
| 0.73 |      | 0.9  | 🔴    |
| 0.66 | 0.73 | 0.81 | 0.73 |

So new state will be

| 0.71 | 0.74 | 0.86 | 🟢    |
| ---- | ---- | ---- | ---- |
| 0.66 |      | 0.39 | 🔴    |
| 0.55 | 0.46 | 0.36 | 0.22 |


---
[Prev](../01-bellman-equation/README.md) | **[Home](../../../README.md)** | [Next](../03-plan-policy/README.md)
