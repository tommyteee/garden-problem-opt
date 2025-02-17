Nonlinear Optimization Using Pyomo and IPOPT

![image](https://github.com/user-attachments/assets/6a77152e-3260-4640-821a-544603e806ed)


Overview

This project formulates and solves a nonlinear optimization problem to maximize the product of two variables x and y while ensuring that they satisfy a given constraint 2x + y ≤ 100. The optimization is implemented using Pyomo and solved with the IPOPT solver for nonlinear programming.

Key Features

Models nonlinear optimization using Pyomo

Ensures bounded constraints on variables

Uses IPOPT, a solver for nonlinear programming (NLP)

Installation

1. Install Required Packages

Ensure you have the following dependencies installed:
pip install pyomo numpy

2. Install IPOPT Solver

Since this project uses IPOPT, you need to download and configure it:

Download IPOPT from COIN-OR IPOPT

Ensure IPOPT is installed and set the correct path in the script:

opt = SolverFactory('ipopt', executable='C:\\ipopt\\bin\\ipopt.exe')

How to Run the Project

Ensure IPOPT is installed and correctly configured.

Run the Python script:

python nonlinear_optimization.py

View the results, which include:

Optimal values of x and y

Maximum product (A = x*y) under the given constraint
