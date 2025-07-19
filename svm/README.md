# SVM Sentiment Classification - AI/ML Learning

This notebook demonstrates a basic implementation of Support Vector Machine (SVM) for sentiment classification using Python and Scikit-learn.

---

## Dataset

**Sentiment Text Dataset**  
The dataset consists of labeled text samples categorized by sentiment (positive or negative). The objective is to predict the sentiment class based on the text data.

---

## Features of This Notebook

- Load and explore the sentiment dataset  
- Handle missing values using `SimpleImputer`  
- Convert text to numerical form using **TF-IDF Vectorizer**  
- Scale and preprocess features using **Scikit-learn Pipelines**  
- Split data into training and testing sets  
- Train an **SVM classifier** using the RBF kernel  
- Evaluate performance using:
  - Accuracy Score  
  - Precision, Recall, and F1-Score  
  - Confusion Matrix  
- Visualize results using:
  - Bar plot of prediction distribution  
  - Confusion Matrix heatmap

---

## Libraries Used

- `pandas`  
- `numpy`  
- `seaborn`  
- `matplotlib`  
- `scikit-learn`

---

## Model Summary

Support Vector Machine (SVM) is a supervised learning algorithm used for classification tasks. It identifies the optimal decision boundary (hyperplane) that best separates different classes in the feature space. The RBF (Radial Basis Function) kernel allows SVM to perform non-linear classification by transforming the input space.

---

## Learning Objective

This notebook is part of a structured learning path aimed at understanding and implementing core machine learning algorithms with Python, focusing on practical application and result interpretation using real-world datasets.


