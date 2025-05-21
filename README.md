# Flow Matching: Mapping Noise to a Target Point

This project demonstrates a simple implementation of **Flow Matching** using a neural network to learn a vector field that maps random noise points in 2D space to a single target point.

## Overview

Flow Matching is a simulation-free training method for continuous normalizing flows (CNFs). This example focuses on learning a deterministic vector field that transforms many noise points into a predefined target.

## What’s Included

- A neural network (`VectorFieldNet`) that models the time-dependent vector field \( v_\theta(t, x) \).
- A simple training loop using synthetic 2D noise and a fixed target.
- Visualization of the learned vector field over a grid.

## Run the Code

### Requirements
- Python 3.8+
- PyTorch
- matplotlib

```bash
pip install torch matplotlib
