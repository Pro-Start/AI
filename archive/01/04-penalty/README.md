# 04 - Leaving a Penalty

Here every move is marked as a penalty. The goal is to *reach the end of the maze* or *get to reward* as fast as possible.

Based on the [optimal plan](../03-plan-policy/README.md)

| ➡️   | ➡️   | ➡️   | 🟢   |
| --- | --- | --- | --- |
| ⬆️   |     | ⬅️   | 🔴   |
| ⬆️   | ⬅️   | ⬅️   | ⬇️   |

Setting penalty for every move, point distribution will be

| -0.1 | -0.1 | -0.1 | 🟢    |
| ---- | ---- | ---- | ---- |
| -0.1 |      | -0.1 | 🔴    |
| -0.1 | -0.1 | -0.1 | -0.1 |

So optimal path will become

| ➡️   | ➡️   | ➡️   | 🟢   |
| --- | --- | --- | --- |
| ⬆️   |     | ⬆️   | 🔴   |
| ⬆️   | ⬅️   | ⬆️   | ⬅️   |


---
[Prev](../03-plan-policy/README.md) | [Home](../../../README.md) | [Next](../03-plan-policy/README.md)