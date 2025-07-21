# Logic Gates with PyTorch

This project implements simple neural networks to learn basic logic gates — **AND**, **OR**, and **XOR** — using PyTorch.

## Overview

- **AND** and **OR** gates are linearly separable and modeled with a single linear layer.
- **XOR** gate is non-linearly separable and modeled using a small multi-layer network with Tanh activations.
- Uses `BCEWithLogitsLoss` and Adam optimizer for training.

## Features

- Flexible model architecture based on gate type.
- Separate training loops with customized epochs and learning rates.
- Predicts output probabilities and binary classes after training.

## Usage

1. Clone the repository.
2. Install PyTorch if not installed: `pip install torch`
3. Run the training script or Jupyter notebook.
4. See predictions printed in the console.
