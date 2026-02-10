# Principal Component Analysis (PCA) – Formative Assignment 2

This repository presents my implementation of **Principal Component Analysis (PCA)** as part of **Formative Assignment 2** for the Advanced Linear Algebra chapter.

The project focuses on applying core linear algebra concepts such as covariance, eigenvalues, eigenvectors, and variance decomposition to analyze and reduce the dimensionality of an African malaria dataset using **NumPy-based computations only**.

---

## Context and Objective

High-dimensional datasets often contain redundant or correlated information. PCA provides a mathematical way to transform such data into a lower-dimensional space while retaining the most significant patterns.

The objective of this project is to:
- implement PCA **from first principles**,
- understand how variance is distributed across components,
- and visualize how dimensionality reduction affects real-world data.

---

## Dataset Description

**Dataset used:**  

`DatasetAfricaMalaria.csv`

The dataset contains malaria-related indicators collected across African regions. It includes multiple numerical features and initially contained missing values.

Only numerical attributes were considered for PCA, ensuring compatibility with linear algebra operations.

---

## Implementation Overview

All steps of PCA were implemented manually without relying on high-level machine learning libraries:

- Loading and inspecting the dataset
- Cleaning the data by replacing missing values with feature means
- Standardizing features to remove scale bias
- Constructing the covariance matrix
- Computing eigenvalues and eigenvectors
- Ranking principal components by explained variance
- Selecting components based on cumulative variance contribution
- Projecting the data onto a reduced feature space
- Visualizing the results before and after PCA

The full implementation is available in the notebook below.

**Notebook:**  

`PCA_Formative_2_AdossiFredWilliam.ipynb`

---

## Technical Requirements

To run this project locally, ensure the following dependencies are installed:

- Python 3.x
- NumPy
- Pandas
- Matplotlib

Install them using:

```bash
pip install numpy pandas matplotlib
```

## How to Run

**1.** Clone the repository:

```bash
git clone https://github.com/Adossi-design/Formative-2---PrincipleComponentAnalysis.git
```

**2.** Open the project directory.

**3.** Launch Jupyter Notebook:

```bash
jupyter notebook
```

**4.** Open PCA_Formative_2_AdossiFredWilliam.ipynb and execute all cells in order.

## Results

- A lower-dimensional representation of the malaria dataset

- Explained variance distribution across principal components

- Visual evidence of variance preservation after dimensionality reduction
