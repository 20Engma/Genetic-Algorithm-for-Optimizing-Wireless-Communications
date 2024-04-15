
---

# Genetic Algorithm for Optimizing Wireless Communications

## Project Overview
This project implements a genetic algorithm to optimize the Free Space Path Loss (FSPL) model, adjusted for a specific angle, for wireless communications systems. The objective is to enhance the accuracy of predictive models used in estimating path loss in wireless transmissions, contributing to better communication quality and system reliability.

## Features
- **FSPL Model Adjustment**: Incorporates angle adjustments to the standard FSPL model to reflect practical transmission conditions more accurately.
- **Genetic Algorithm Optimization**: Utilizes a genetic algorithm to find the optimal parameters that minimize the prediction error in path loss.
- **Performance Metrics**: Tracks several metrics such as average fitness, convergence, and genetic diversity to evaluate the effectiveness of the genetic algorithm.

## Installation
To run this project, you need Python 3.x and several dependencies listed below. You can install the required libraries using `pip`:
```bash
pip install numpy pandas matplotlib scikit-learn deap
```

## Usage
To execute the program, navigate to the project directory and run the Jupyter notebook:
```bash
jupyter notebook Genetic_Algorithm.ipynb
```
Follow the instructions within the notebook to perform the optimization and visualize the results.

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- DEAP library for evolutionary algorithms



