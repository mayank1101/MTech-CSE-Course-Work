# Neural Networks and CNNs from Scratch

Group assignment for Deep Learning (CSC004P5E), M.Tech Semester 3.

The project explores the mechanics of neural networks without relying on a high-level deep-learning framework for the core forward and backward operations.

## Implemented concepts

- Feed-forward neural-network inference, backpropagation, and training
- CNN forward propagation, including convolution and pooling operations
- CNN backward propagation
- NumPy-based calculations and Python `unittest` test cases

## Layout

- [`neural network/`](neural%20network/) contains the feed-forward neural-network implementation and test scripts.
- [`cnn_forward_propagation/`](cnn_forward_propagation/) contains CNN forward-pass functions and tests.
- [`cnn_backward_propagation/`](cnn_backward_propagation/) contains CNN backward-pass functions and tests.
- [`colab notebook/`](colab%20notebook/) contains the assignment notebook.
- [`Presentation/`](Presentation/) contains the project presentation and supporting images.

## Setup and compatibility

The Python modules primarily require NumPy:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install numpy jupyter
```

This is historical coursework rather than a packaged Python library. Imports depend on the working directory, and some test files may need path or import corrections before they run on a current Python version.

## Contributors

- [Mayank Sharma (2019PCS0006)](https://github.com/mayank1101)
- [Nikita Sharma (2019PCS0007)](https://github.com/nikitasharma9010)
- [Pranav Joshi (2019PCS0022)](https://github.com/PranavJoshi1)
