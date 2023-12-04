# Mixed Integer Programming Solution

## Description

This repository contains the implementation of a Mixed Integer Programming (MIP) solution for optimizing a linear problem with integer constraints. The problem focuses on maximizing the objective function `x + 10y` under specific linear constraints.

## Problem Statement

The problem is formulated as follows:

- Maximize the objective function: `x + 10y`
- Subject to the constraints:
  - `x + 7y ≤ 17.5`
  - `0 ≤ x ≤ 3.5`
  - `0 ≤ y`
  - `x`, `y` are integers

## Solution Approach

The solution employs a manual enumeration strategy to evaluate feasible integer pairs `(x, y)` within the given constraints. Each pair is tested against the objective function, and the optimal solution is determined based on the maximum value achieved.

## How to Run

Instructions for running the solution:

   git clone [URL-of-the-repository]
   cd [repository-name]
   python mip_solution.py

## Requirements

- Python
- Google Colab
