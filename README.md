# Support-Vector-Machine
This repository contains a from-scratch implementation of Support Vector Machines in Python. The code includes functions for data loading, kernel transformation, and the SMO algorithm. It demonstrates the core concepts of SVM, including margin maximization and the kernel trick, without relying on external machine learning libraries.

# Support Vector Machine (SVM) Implementation from Scratch

This repository contains a Python implementation of Support Vector Machines (SVM) built from scratch. The project demonstrates the core concepts of SVM, including the Sequential Minimal Optimization (SMO) algorithm and kernel transformations.

## Features

- Data loading and preprocessing
- SMO algorithm implementation
- Kernel transformations (linear and RBF)
- Support for binary classification problems
- Calculation of weight vector

## Files

- `SupportVec.ipynb`: Jupyter notebook containing the SVM implementation and examples
- `testSet.txt`: Sample dataset for testing the SVM algorithm

## Usage

To use this implementation:

1. Clone the repository
2. Open the `SupportVec.ipynb` Jupyter notebook
3. Run the cells to see the SVM algorithm in action

## Learning Outcomes

This project helps in understanding:

- The principles behind Support Vector Machines
- How the SMO algorithm optimizes the SVM objective function
- The role of kernel functions in SVM for non-linear classification
- The process of calculating the separating hyperplane

## Implementation Details

The SVM implementation includes:

- `smoSimple`: A simplified version of the SMO algorithm
- `smoP`: The full Platt SMO algorithm
- `kernelTrans`: Function for applying kernel transformations
- `calcWs`: Function for calculating the weight vector

Feel free to explore, learn, and contribute!
