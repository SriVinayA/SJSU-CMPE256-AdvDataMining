# Linear Optimization Project

## Overview
This project demonstrates the application of linear programming to solve a linear optimization problem. The goal is to maximize an objective function subject to a set of linear constraints. This example is particularly useful in various fields of engineering, economics, and operational research.

## Objective
Maximize the objective function:
3x + 4y


### Subject to the Constraints:
1. `x + 2y ≤ 14`
2. `3x - y ≥ 0`
3. `x - y ≤ 2`

## Methodology
The project utilizes the `scipy.optimize.linprog` method from the SciPy library in Python, which is designed to solve linear programming problems. The approach involves converting the maximization problem into a minimization problem (as `linprog` minimizes by default) and defining the constraints and variable bounds appropriately.

## Files in the Repository

- `linear_optimization.py`: Contains the Python code implementing the linear optimization.

## Installation and Running the Project

### Prerequisites
- Python 3.x
- Pip (Python package installer)

### Setup
1. Clone the repository:
git clone [URL to the repository]

2. Install the required packages:
pip install -r requirements.txt


### Executing the Program
Run the Python script:
python linear_optimization.py


## Results
The solution provides the optimal values for x and y that maximize the objective function, given the constraints.

## Contributing
Contributions to enhance the project are welcome. Please follow the standard procedures for contributing to GitHub projects.
