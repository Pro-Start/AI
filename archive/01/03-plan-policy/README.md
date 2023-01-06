# 03 - Policy and Plan

### Policy

It is a function that maps the current state of the environment to an action. 

It is based on **Bellman equation**.

Deals with the **getting to Reward**.

| ➡️   | ➡️   | ➡️   | 🟢   |
| --- | --- | --- | --- |
| ⬆️   |     | ⬆️   | 🔴   |
| ⬆️   | ➡️   | ⬆️   | ⬅️   |



### Plan

It is a sequence of actions that will be executed by the agent. 

It is based on **Markov Decision Process**.

Deals with the problem of **finding the optimal plan**.

| ➡️   | ➡️   | ➡️   | 🟢   |
| --- | --- | --- | --- |
| ⬆️   |     | ⬅️   | 🔴   |
| ⬆️   | ⬅️   | ⬅️   | ⬇️   |


---
[Prev](../02-mdp/README.md) | **[Home](../../../README.md)** | [Next](../04-penalty/README.md)