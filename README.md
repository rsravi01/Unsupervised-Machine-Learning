# Unsupervised-Machine-Learning
Unsupervised machine learning uncovers patterns in data without labeled outcomes. Clustering groups data points based on similarity, with K-Means, DBSCAN, and Hierarchical Clustering being widely used methods.

Algorithms Overview

K-Means Clustering

Objective: Minimizes distances between points and cluster centroids.

Key Parameters: Number of clusters (k).

Pros: Fast, easy to interpret. Cons: Sensitive to outliers.

DBSCAN

Objective: Groups data by density, identifying noise and outliers.

Key Parameters: eps (distance), min_samples (density).

Pros: Handles arbitrary shapes. Cons: Struggles with varying densities.

Hierarchical Clustering

Objective: Builds a hierarchy of clusters.

Types: Agglomerative, Divisive.

Pros: No predefined cluster count. Cons: Computationally expensive.

Implementation Steps

Preprocess Data: Handle missing values, normalize features.

Choose Algorithm: Based on data and goals.

Set Parameters: Define parameters for the chosen method.

Fit Model: Train the algorithm.

Evaluate Results: Use metrics like silhouette score.

Visualize Clusters: Scatter plots or dendrograms.

Requirements

Python 3.7+

Libraries: numpy, pandas, matplotlib, scikit-learn, scipy
