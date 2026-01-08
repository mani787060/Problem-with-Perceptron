# Problem with Perceptron

## Overview
This project demonstrates the **limitations of the Perceptron algorithm** when dealing with non-linearly separable data. Using simple logical operations (AND, OR, XOR), we show where the perceptron succeeds and where it fails.

## Concepts Demonstrated
- Linear vs Non-linear separability
- Perceptron behavior on logical gates
- Why XOR cannot be solved by a single perceptron
- Decision boundary visualization

## Datasets Used
Three datasets are manually created:
- AND logic gate
- OR logic gate
- XOR logic gate

Each dataset is represented using a Pandas DataFrame.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Mlxtend

## Key Observation
- AND and OR datasets are **linearly separable** → Perceptron works
- XOR dataset is **not linearly separable** → Perceptron fails

## Purpose of This Project
This notebook is part of my **Deep Learning learning journey**, aimed at understanding the theoretical limitations of single-layer models and motivating the need for **Multi-Layer Perceptrons (MLPs)**.
