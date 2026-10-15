## Name: Hailemariam Dagnew
ID: UGR/0344/16 
## Assignment 1
Practical: Data Exploration & Foundational Math
This repository contains the practical assignment. The work covers initial data cleaning, descriptive statistical analysis, visualization, vector operations, and feature scaling using a student performance dataset.

## Contents

- `SECT4451_Practical_2.ipynb`: Complete Jupyter Notebook containing all code, generated plots, and written responses.

## Practical Overview

The assignment is divided into six main sections:

- **Part A — Inspect and Clean:** Identified missing entries and an extreme outlier (`study_hours = 50`), handled corrupted values, and confirmed matrix shapes and feature roles.
- **Part B — Summarize:** Computed summary statistics (mean, median, and standard deviation) across features and provided key observations on data distributions.
- **Part C — Visualize:** Generated a distribution histogram of final scores and a scatter plot evaluating the relationship between study hours and performance.
- **Part D — Correlation and Causality:** Calculated the Pearson correlation coefficient ($r$) and analyzed confounding variables affecting academic outcomes.
- **Part E — Vectors and Dot Product:** Extracted a student feature vector $\mathbf{x}$, assigned weight vector $\mathbf{w}$ and bias $b$, and computed predictions using NumPy vector dot products.
- **Part F — Scaling:** Standardized features (`study_hours`, `previous_mark`) and detailed why unscaled features distort distance-based algorithms such as K-Nearest Neighbors (KNN).

## Requirements

To run the notebook locally, install the required packages:

```bash
pip install numpy pandas matplotlib
