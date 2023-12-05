# CMPE-255-Clustering

# Types of Clustering Algorithms 📊

This README provides an overview of various types of clustering algorithms used in unsupervised machine learning.

## Introduction ℹ️

Clustering is an unsupervised learning technique that involves grouping similar data points together. Different clustering algorithms utilize distinct approaches to cluster data based on various criteria.

## Types of Clustering Algorithms 🛠️

### 1. K-Means Clustering
- **Description:** Divides data into 'k' clusters based on centroids.
- **Advantages:** Simple, easy to implement, works well with large datasets.
- **Disadvantages:** Sensitive to initial centroid placement.

### 2. Hierarchical Clustering
- **Description:** Forms clusters in a tree-like hierarchical structure.
- **Advantages:** No need to specify the number of clusters beforehand.
- **Disadvantages:** Less scalable for larger datasets.

### 3. Density-Based Spatial Clustering of Applications with Noise (DBSCAN)
- **Description:** Identifies clusters based on areas with higher density.
- **Advantages:** Can find arbitrary-shaped clusters, robust to outliers.
- **Disadvantages:** Sensitive to parameters (epsilon, min_samples).


### 4. Gaussian Mixture Models (GMM)
- **Description:** Assumes data points are generated from a mixture of several Gaussian distributions.
- **Advantages:** Flexible in accommodating different shapes of clusters.
- **Disadvantages:** Sensitive to initialization values.

### 5. Agglomerative Clustering
- **Description:** Starts with individual data points and merges them into clusters.
- **Advantages:** Produces a hierarchy of clusters.
- **Disadvantages:** Computationally intensive for larger datasets.

