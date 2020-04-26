# outbreak-simulation
This repository aims to build a mathematical model describing the spread of the covid-19 virus based on activity driven networks (project for TU/Delft Complex Networks course)

## Setup
To run the notebooks from this repository two python packages are needed. You can install these using pip.

```bash
pip install simpy
pip install nxsim
```
*Note:* you can either use a virtual environment or install all pip packages globally.

## Core functions
Workers.py contains the core functions implementing the basic simulation, social distancing, incubation period, and self-quarantine (all stochastic).

## Simulations
"mit_network_sim.ipynb" generates simulation for combinations of the parameters mentioned in core functions.
