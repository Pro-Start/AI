# 01 - Bellman Equation

The Bellman equation is a fundamental equation in dynamic programming. It is used to solve the optimal control problem. The Bellman equation is     

```
V*(s)= max[R(s,a)+ Ī³ Vā(sā²)]
```

where,
 
> $V^*$ is the value function, 
> 
> $R(s,a)$ is the reward function, 
> 
> s is the State,
>
> a is the Action,
> 
> $\gamma$ is the discount factor. 
 

### Maze Example

| [ - ] | [ - ] | [ - ] | š¢     |
| ----- | ----- | ----- | ----- |
| [ - ] |       | [ - ] | š“     |
| [ - ] | [ - ] | [ - ] | [ - ] |


Considering $\gamma$ = 0.9, the value function for the maze will be 

| 0.81 | 0.9  | 1    | š¢    |
| ---- | ---- | ---- | ---- |
| 0.73 |      | 0.9  | š“    |
| 0.66 | 0.73 | 0.81 | 0.73 |

---

**[Home](../../../README.md)** | [Next](../02-mdp/README.md)