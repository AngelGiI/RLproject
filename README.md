# Reinforcement Learning Project: Smart Grid Battery Optimization

This repository contains the implementation and results of a project that applies reinforcement learning to optimize the operation of a battery in a smart grid context.

---

## Overview

The project focuses on developing a control strategy for the daily operation of a car battery attached to the electricity grid. Using 3 years of past electricity price data, the goal is to:

- Minimize electricity costs by deciding when to charge or discharge the battery.
- Account for stochastic future electricity prices and operational constraints.

---

## Key Features
1. **Environment Implementation**:
   - Custom environment built using [Gymnasium](https://gymnasium.farama.org/).
   - Simulates battery operation, electricity prices, and car availability.

2. **Algorithms**:
   - Baseline algorithms for initial comparison.
   - Reinforcement Learning (RL) for decision-making under uncertainty.

3. **Performance Evaluation**:
   - Visualizations of battery operations.
   - Validation using unseen time series data.
