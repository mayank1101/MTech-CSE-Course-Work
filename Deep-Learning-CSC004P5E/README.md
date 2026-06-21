# Deep Learning (CSC004P5E)

M.Tech, Semester 3 — Instructor: Dr. Yamuna Prasad

This directory contains theory assignments, lab exercises, and a group project implementing neural-network and convolution operations from scratch.

## Topics

- Loss functions and gradient-descent variants
- Computation graphs and backpropagation
- Feed-forward neural networks
- Convolutional neural networks
- Recurrent neural networks
- Autoencoders
- Generative adversarial networks

## Contents

- [`Theory Assignments/`](Theory%20Assignments/) contains written work on gradient descent, cross-validation, and weekly theory topics.
- [`Lab Assignments/`](Lab%20Assignments/) contains notebooks and Python scripts for loss visualization, computation graphs, gradient descent, and CNN forward/backward operations.
- [`DL-Course-Assignment/`](DL-Course-Assignment/) contains the from-scratch neural-network/CNN group assignment, tests, a Colab notebook, and presentation material.

## Working with the code

Use a virtual environment and install dependencies for the specific exercise being run. The lab material primarily uses NumPy, pandas, SciPy, scikit-learn, scikit-image, and Jupyter:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install jupyter numpy pandas scipy scikit-learn scikit-image
jupyter lab
```

The exercises are an academic archive and dependencies are not pinned. Some imports use APIs from older package versions and may require compatibility changes on a current Python stack.

## Notes

- The historical directory name `gardient descent` is preserved intentionally.
- The course directory does not include a separate license. Refer to the repository root README for licensing details.
