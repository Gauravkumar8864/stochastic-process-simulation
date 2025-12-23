# Empirical Study of Stochastic Processes and Expected Value

## Motivation
Expected value is often used to judge whether a system or strategy is favorable.
This project demonstrates, through simulation, why expected value alone is
insufficient to understand real-world outcomes under randomness.

## What This Project Shows
- Expected value is a long-run property and can be misleading in finite samples
- Variance and tail risk dominate short- and medium-term behavior
- Two systems with equal expected value can have drastically different risk profiles

## Experiments
1. Bernoulli process to study convergence to expected value
2. Random walk to show how risk grows even when expectation is zero
3. Two stochastic games with equal expected value but different variance

## Key Insight
Equal expected value does not imply equal real-world outcomes.
High-variance systems exhibit greater instability and higher probability of extreme losses.

## Tools
Python, NumPy, Matplotlib
