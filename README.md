# SGHMC Algorithm Implementation

Qinzhe Wang (qw92@duke.edu)

Yi Mi (yi.mi@duke.edu)

## Introduction
This project implemented the Stochastic Gradient Hamiltonian Monte Carlo algorithm. Numba, C++ and Cholesky Decomposition were utilized to optimize the performance of the code. The algorithm was applied on simulated dataset and tested on a handwritten digits classification task using the MNIST dataset, compared to SGLD and SGD with momentum methods. The package was created and published on TestPyPI.

## Structure
`application`: Applications code on simulated and real data

`figures`: Reproducible figures

`optimization`: Optimization code using Numba, C++, and Cholesky Decomposition

`report`: Report and original paper

`sghmc`: Source code of SGHMC algorithm

`test`: Test algorithm and package

## Installation
This package is published on TestPyPI.
```
pip install -i https://test.pypi.org/simple/ sghmc-2021
```
Usage.
```
import sghmc
sghmc.sghmc()
```

## Maintainers
Qinzhe Wang (qw92@duke.edu)

Yi Mi (yi.mi@duke.edu)