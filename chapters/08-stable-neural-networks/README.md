# Chapter 8: Stable neural networks and continuous dynamical systems

**Authors:** Matthias J. Ehrhardt, Davide Murari, and Ferdia Sherry

This folder accompanies the chapter on non-expansiveness, stable equilibria, Hamiltonian networks, and stability-aware deep learning.

## Setup and execution

To reproduce the results of the book chapter, set up a Python 3.14 virtual environment, install the requirements listed in `requirements.txt` and run the Jupyter notebooks in the subdirectories.

Two experiments are included: 
- `inverse_problem`: studying the solution of a synthetic ill-conditioned inverse problems using stable neural networks, as in Section 6.1 of the chapter,
- `adversarial_robustness`: studying adversarially robust image classification on the FashionMNIST dataset, as in Section 6.2 of the chapter.

Both experiments can be run within an hour from start to finish on consumer hardware (tested on an M1 Mac with 8 cores), but final trained weights are also provided in `adversarial_robustness` for anyone who wants to skip training the networks.

