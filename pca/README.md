# PCA - MNIST Digit Visualization (AI/ML Learning)

This notebook demonstrates dimensionality reduction using **Principal Component Analysis (PCA)** to visualize high-dimensional image data from the MNIST dataset in 2D.

## Dataset

**mnist_test.csv**

This dataset contains:
- 784 pixel values representing grayscale images (28x28)
- A `label` column indicating the digit (0–9)

## Objectives

- Load and prepare the MNIST test dataset
- Standardize pixel features
- Apply PCA to reduce 784 features to 2 dimensions
- Visualize digit clusters in 2D space using PC1 and PC2

## Features of This Notebook

- Feature scaling using `StandardScaler`
- Dimensionality reduction using `sklearn.decomposition.PCA`
- Visualize digit distribution using:
  - 2D scatterplot of PC1 vs PC2
- Clear labeling and coloring of digit classes using Seaborn

## Libraries Used

- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

## Summary

Principal Component Analysis (PCA) was used to project high-dimensional image data into a lower-dimensional space. The 2D scatterplot of the first two principal components provides insight into how digits are grouped or separated, revealing the underlying structure in the data.

This notebook is part of a series of projects focusing on real-world applications of unsupervised machine learning techniques.


