# Assignment 1 COMP532 - University of Liverpool

This project aims to implement a multi-armed bandit problem.

We used an incremental method to evaluate and implementation the optimal action and reward for playing multi-bandit arms. <br>

Fix values for our assignments:
1. Number or arms: 20
2. Number of problems: 2000
3. ϵ for ϵ-greedy action: 0, 0.1 and 0.01

Given $Q_n$ and the $n$ th reward, $R_n$, the new average of all n rewards can be computed by

$$
    Q_{n+1} = Q_n + \frac{1}{n} [R_n - Q_n]
$$
