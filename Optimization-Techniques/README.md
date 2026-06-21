# Optimization Techniques (SC550)

M.Tech, Semester 2

This directory contains written assignments and a notebook implementation of the transportation problem.

## Topics

- Linear-algebra review and linear-programming fundamentals
- Algebraic and graphical solution methods
- Simplex, Big M, and two-phase methods
- Duality
- Transportation and assignment problems, including unbalanced and maximization variants
- Two-player zero-sum games (`n × 2`, `2 × n`, and `m × n` cases)

## Contents

- [`Online Assignments/`](Online%20Assignments/) contains submissions on the Big M method, two-phase method, duality, simplex minimization, and transportation problems.
- [`Coding Assignments/Transportation Problem.ipynb`](Coding%20Assignments/Transportation%20Problem.ipynb) contains the transportation-problem implementation.
- [`Coding Assignments/Transportation Problem.html`](Coding%20Assignments/Transportation%20Problem.html) is a rendered snapshot of that notebook.

## Using the notebook

Create a Python environment, install Jupyter and any imports requested by the notebook, then start Jupyter from this directory:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install jupyter
jupyter lab
```

Dependencies are not pinned, so older notebook code may require minor changes with current packages.

## License

Original code in this directory is provided under the [MIT License](LICENSE). PDFs and other third-party material retain their original rights.
