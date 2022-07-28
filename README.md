# Quantum-approximate-optimisation-algorithms-for-real-world-scenarios---Strangeworks
Womanium Quantum Hackathon 2022

## Challenge Introduction
Current noisy intermediate scale quantum computers (NISQ) may be well suited to solving quantum approximate optimisation algorithms (QAOA) with some promising initial proof of principle results. These can be applied to solve a wide variety of problems such as the max-cut or traveling salesman problems, which are extremely relevant to real world scenarios useful for optimizing global supply chains for example. Classically they are extremely difficult to solve for an optimal solution, with a computational cost that scales exponentially with the number of parameters. 
We find that what many of our partners really want at this stage is to know how much quantum solutions to these problems are going to cost! This is very important because time on quantum hardware is currently extremely expensive. While they of course are interested in defining and quantifying how well these methods will actually work, their real world budgeting constraints is what will most impact the viability as far as they see it. 
This project will involve creating and testing a QAOA algorithm on a chosen graph. The accuracy of this method will then be tested upon varying the number of classical optimization steps, the depth of the quantum circuit and the number of measurements required on the quantum device at each step etc. This will then allow us to define the total classical hardware time and the total quantum hardware time, giving us an initial estimate for the overall cost of running such an algorithm.
For many real world scenarios we do not necessarily need the most optimal solution, just one that is better than those currently utilized, so we will be judging submissions based on an analysis which balances the overall cost of the routine with the quality of the solution. Additional points will be given for the presentation and interpretation of the data in terms of the viability of these methods as the graph size and complexity are increased. We will also be looking for more advanced offerings, such as methods for post processing the quantum measurement results to better refine the classical solution of the graph and sufficient explorations in the space of connected graphs as well as explorations of the parameter space for the variational coefficients.

### Installing Python and VS code

We recommend opening this notebook with VS code. A handy guide for doing so is here: https://code.visualstudio.com/docs/python/python-tutorial   

For those that don't know, a Jupyter notebook is a convenient way of running python code, where code segments are seperated into "cells". It is then possible to run each cell one by one, usually it is good practice to start at the top and run each subsequent cell one by one. Variables are typically global i.e. variables defined in cells can be called in cells positioned below. 

The only prerequisite is that you can run the first cell in the notebook "Intro.ipynb". This checks the version of python you currently have installed. If you can run this successfully, then you should be able to run the rest of the notebook. 

