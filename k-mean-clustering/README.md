# K-Means Clustering - Customer Segmentation (AI/ML Learning)

This notebook demonstrates the implementation of **K-Means Clustering** using Python and `scikit-learn` for unsupervised customer segmentation based on shopping behavior.

---

## Dataset

**Mall_Customers.csv**  
This dataset contains information about mall customers, including:

- `CustomerID`: Unique identifier
- `Gender`: Male/Female
- `Age`: Customer age
- `Annual Income (k$)`: Income in thousands
- `Spending Score (1-100)`: Assigned score based on spending behavior

---

## Objective

To group customers into meaningful segments using **K-Means clustering**, enabling targeted marketing strategies.

---

## Features of This Notebook

- Load and inspect the dataset
- Encode categorical features (`Gender`)
- Scale data using `StandardScaler`
- Use **Elbow Method** to determine optimal number of clusters
- Apply **KMeans Clustering**
- Evaluate clustering using:
  - Silhouette Score
  - Calinski-Harabasz Score
  - Davies-Bouldin Score
- Visualize:
  - Elbow Method graph
  - Cluster distribution in 2D feature space
  - Silhouette plot for individual sample scores
  - Bar plot of clustering evaluation metrics

---

## Libraries Used

- `pandas` – Data manipulation
- `numpy` – Numerical operations
- `matplotlib` – Plotting
- `seaborn` – Advanced plotting
- `scikit-learn` – Clustering & preprocessing

---

## Clustering Evaluation Metrics

| Metric                   | Purpose                                     | Ideal Value |
|--------------------------|---------------------------------------------|-------------|
| Silhouette Score         | Measures separation and cohesion of clusters | Closer to 1 |
| Calinski-Harabasz Score  | Higher is better separation between clusters | High        |
| Davies-Bouldin Score     | Measures overlap between clusters            | Lower       |

---

##  Model Summary

**K-Means Clustering** is an unsupervised algorithm that partitions the dataset into **K distinct, non-overlapping groups** based on similarity. It iteratively optimizes cluster centers to minimize intra-cluster variance (**WCSS**).

---

##  Output Visualizations

- **Elbow Plot** to select `k` using WCSS
- **Cluster Plot** for `Annual Income` vs `Spending Score`

---

##  Conclusion

This project is part of a structured journey to explore machine learning models and understand how unsupervised algorithms like **K-Means** can reveal patterns in real-world datasets.


