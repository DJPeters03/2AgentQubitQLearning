# 2-Agent Qubit Q-Learning Simulator

## Overview

This project demonstrates a reinforcement learning simulation with two
agents operating on a 2-qubit quantum state. Each agent chooses from 7
quantum actions (I, X, Z, H, S, RZ, and E for entanglement) to maximize
entanglement, measured by concurrence.

## Features

-   Two independent Q-learning agents
-   Discrete entanglement state buckets (6 levels)
-   Reward shaped by changes in concurrence
-   Special coordinated action (E) applies CNOT gate
-   Visualization of amplitudes, probabilities, entanglement bar, and
    Q-tables
-   Adjustable parameters: epsilon (exploration), alpha (learning rate),
    gamma (discount)

## Usage

1.  Open `2AgentQubitQLearning.html` in a modern browser.
2.  Use the controls to step through or run training episodes.
3.  Observe how agents evolve policies to generate entanglement.

## Purpose

This simulator is designed for educational use, combining quantum
computing basics with reinforcement learning, to illustrate how simple
agents can learn to coordinate for entanglement.
