# Feature Selection implementing Coati Optimization Algorithm (FSCOA)

## Overview

This repository contains the official implementation of FSCOA, a novel and economical approach for Software Fault Prediction (SFP). Feature selection is a crucial step in SFP to handle large-scale software metrics and reduce the costs of rectifying vulnerabilities.

FSCOA leverages the Coati Optimization Algorithm to select the most relevant feature subsets, significantly reducing data dimensionality while improving classification accuracy.

## Key Contributions

**Novel Feature-Selection:** Application of the Coati Optimization Algorithm (COA) for wrapper-based feature selection.

**Superior Performance:** Outperformed PSO, ACO, GA, and DE in over 90% of test cases.

**Efficiency:** Reduced the feature space to less than 50% of the original metrics while maintaining or improving accuracy.

**Statistical Validation:** The model’s superiority is statistically proven using the Friedman Test (holding Rank 1 in all cases) and the Holm Test.

## Experimental Setup

The algorithm was evaluated using 12 open-source software defect datasets and embedded with four popular classifiers:

1. KNN (K-Nearest Neighbors)
2. QDA (Quadratic Discriminant Analysis)
3. DT (Decision Tree)
4. NB (Naive Bayes)

## Publication

This work has been published in SN Computer Science Journal (Springer Nature).

Title: Cost-Effective Prediction Model for Optimal Selection of Software Faults Using Coati Optimization Algorithm

[DOI: 10.1007/s42979-025-03953-y](https://doi.org/10.1007/s42979-025-03953-y)

## Getting Started
### Prerequisites

Ensure you have Python installed along with the following libraries:

* numpy
* pandas
* scikit-learn
* matplotlib

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
