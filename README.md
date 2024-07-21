# Singular Value Decomposition (SVD) Data Mining

   This project demonstrates the implementation of [**Singular Value Decomposition (SVD)**](https://en.wikipedia.org/wiki/Singular_value_decomposition) using various popular libraries such as [NumPy](https://numpy.org/), [SciPy](https://scipy.org/), and [PyTorch](https://pytorch.org/). Each implementation is contained within its own [Jupyter Notebook](https://jupyter.org/), providing a comprehensive and detailed guide on how to perform SVD using these different tools.

## Rep
ository Structure

   - [Implementation of SVD using NumPy](SVD_Implement_With_NumPy.ipynb)
   - [Implementation of SVD using SciPy](SVD_Implement_With_Scipy_NumPy.ipynb)
   - [Implementation of SVD using PyTorch](SVD_Implement_With_PyTorch.ipynb)

## Dataset

   The dataset used in this project is the [`heart_statlog_cleveland_hungary_final.csv`](heart_statlog_cleveland_hungary_final.csv), which combines heart disease data from various sources.
   This dataset includes numerous attributes related to heart disease, and it is a common benchmark for evaluating classification algorithms.

## Requirements

   To run these notebooks, you will need the following libraries installed in your Python environment:

   | Library      | Version     | Implementation                |
   |--------------|-------------|-------------------------------|
   | NumPy        | >= 1.21.0   | All implementations           |
   | SciPy        | >= 1.7.0    | SVD_Implement_With_Scipy_NumPy|
   | PyTorch      | >= 1.9.0    | SVD_Implement_With_PyTorch    |
   | Pandas       | >= 1.3.0    | All implementations           |
   | Seaborn      | >= 0.11.0   | SVD_Implement_With_PyTorch    |
   | TensorFlow   | >= 2.5.0    | All implementations           |
   | Matplotlib   | >= 3.4.2    | All implementations           |
   | Scikit-Learn | >= 1.0.0    | All implementations           |

   You can install these dependencies using pip:

```bash
   pip install numpy scipy torch tensorflow pandas seaborn matplotlib scikit-learn
```

## Overview

   * Implement With NumPy

   This code details the step-by-step process of implementing SVD from scratch using NumPy.

      It covers the following steps:
      - Data preprocessing
      - Custom implementation of matrix transpose
      - Custom implementation of eigenvalue decomposition
      - Computing the singular values
      - Computing left and right singular vectors
      - Dimensionality reduction

   * Implement With SciPy and NumPy

   This code shows how to leverage SciPy's linear algebra capabilities to implement SVD.

      It includes:
      - Using SciPy for matrix operations
      - Performing SVD directly using SciPy's `svd` function
      - Verifying the results against the NumPy implementation
      - Dimensionality reduction

   * Implement With PyTorch

   Here, we utilize PyTorch for implementing SVD, which is particularly useful for those familiar with deep learning frameworks.

      This notebook covers:
      - Utilizing PyTorch tensors for data representation
      - Implementing SVD using PyTorch's linear algebra functions
      - Comparing performance and results with NumPy and SciPy implementations
      - Dimensionality reduction


## Results and Analysis

   Each code concludes with a section on results and analysis, where we evaluate the performance of the LDA implementations on the heart disease dataset.
   We visualize the transformed data and discuss the effectiveness of LDA in dimensionality reduction and classification.

## License

   This repository is licensed under the Apache License 2.0.
   See the [LICENSE](./LICENSE) file for more details.