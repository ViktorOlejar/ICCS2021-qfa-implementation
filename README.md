# Implementing Quantum Finite Automata Algorithms on Noisy Devices

This repository hosts the source code used to create the circuits used to produce the results presented in ICCS 2021 paper Implementing Quantum Finite Automata Algorithms on Noisy Devices.

## Installation

This project uses `qiskit` to create quantum circuits.

The most straightforward way to set up this project is by using `pipenv`. On macOS, it can be installed using Homebrew via
```bash
brew install pipenv
```
On other platforms, `pip` is the preferred method to install `pipenv`.
```bash
pip install --user pipenv
```

Once `pipenv` is insatlled, a virtual environment can be set up by
```bash
cd /path/to/qfa-implementation
pipenv install
```

Finally, the environment can be activated via 
```bash
pipenv shell
```

To use the notebooks, a ipython kernel should be registered to Jupyter via
```bash
ipython kernel install --user --name=qfa
```
Then this kernel can be accessed from either jupyter lab or jupyter notebooks using the regular interface.

## Demonstration

A simple demonstration of the circuits are provided via Jupyter notebooks.

- [2-State Automata](notebooks/01-two-state.ipynb)
