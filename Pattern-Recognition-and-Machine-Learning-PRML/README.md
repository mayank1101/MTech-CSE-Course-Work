# Pattern Recognition and Machine Learning (IT-542)

M.Tech, Semester 2

This directory contains lecture material, mathematical notes, lab notebooks and questions, a MATLAB exercise, and reference texts for the Pattern Recognition and Machine Learning course.

## Topics

- Multivariate normal distributions and parameter estimation
- Maximum-likelihood estimation
- Bayesian classifiers, decision rules, and naive Bayes
- K-nearest-neighbor and kernel density estimation
- Supervised and unsupervised classification
- K-means and fuzzy K-means clustering
- Principal component analysis and nonlinear dimensionality reduction
- Linear and logistic regression
- Gaussian mixture models and expectation maximization
- Support vector machines

## Contents

- [`lectures/`](lectures/) contains the course presentation modules.
- [`maths/`](maths/) contains supporting notes on probability, EM, mixture models, and graphical models.
- [`lab/`](lab/) contains Jupyter lab work, a MATLAB file, datasets, outputs, and the corresponding questions under `lab/questions/`.
- [`class/`](class/) and [`my books/`](my%20books/) contain reference texts.

## Working with the labs

The notebooks use a mix of scientific Python libraries. Install dependencies as required by the selected notebook:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install jupyter numpy pandas scipy scikit-learn matplotlib
jupyter lab
```

MATLAB or GNU Octave is required for the `.m` exercise. Dependencies are not pinned, and legacy notebooks may require compatibility changes. Notebook checkpoint files are historical committed artifacts; new checkpoints are ignored at the repository root.

## Additional reference

- [NPTEL: Pattern Recognition by C. A. Murthy](https://www.youtube.com/playlist?list=PLbMVogVj5nJQJMLb2CYw9rry0d5s0TQRp)

## License

Original code in this directory is provided under the [MIT License](LICENSE). Books, lecture material, datasets, and other third-party resources retain their original rights.
