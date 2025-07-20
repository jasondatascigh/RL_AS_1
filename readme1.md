## Part 1: Stationary Bandit

Implemented the following methods for the 10-armed testbed:
- Greedy (Q = 0)
- Epsilon-Greedy (ϵ = 0.1)
- Optimistic Initial Values (Q = 2.5)
- Gradient Bandit (α = 0.1)

Each algorithm was run for 2000 time steps, over 1000 independent simulations. Results include:
- Average reward per step
- Percentage of optimal action chosen

## Part 2: Non-Stationary Bandit

Tested algorithm performance under:
- Gradual Drift (μ updated via random walk)
- Mean-Reverting Drift
- Abrupt Change at t = 501 (with and without reset)

Compared epsilon-greedy and gradient bandit under each setting.