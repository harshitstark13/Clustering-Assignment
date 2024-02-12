# Clustering Analysis with Iris Dataset
This repository contains the code and results for clustering analysis performed on the famous Iris dataset using various clustering algorithms: DBSCAN, Hierarchical Clustering, K-Means, and their comparison.

**Iris Dataset**

The Iris dataset is a classic dataset in the field of machine learning and is often used for demonstration purposes. It consists of 150 samples of iris flowers, each belonging to one of three species: setosa, versicolor, or virginica. Each sample has four features: sepal length, sepal width, petal length, and petal width.

**Files**

iris-dataset: This directory contains the raw Iris dataset in CSV format.
gaussian_results_iris.csv: Results of clustering analysis using Gaussian Mixture Model.
hierarchical_results_iris.csv: Results of clustering analysis using Hierarchical Clustering.
kmeans_results_iris.csv: Results of clustering analysis using K-Means.
compared_results_iris.csv: Comparison of clustering results across different algorithms.

**Clustering Algorithms**

**DBSCAN:**
DBSCAN (Density-Based Spatial Clustering of Applications with Noise) is a density-based clustering algorithm that groups together closely packed points while marking outliers as noise. It does not require specifying the number of clusters beforehand and is effective in identifying clusters of arbitrary shapes in noisy datasets.

**Hierarchical Clustering:**
Hierarchical clustering is a method of cluster analysis that builds a hierarchy of clusters. It starts with each data point as a separate cluster and then iteratively merges the closest clusters until only one cluster remains.

**K-Means:**
K-Means is a popular clustering algorithm that partitions the dataset into K clusters by iteratively reassigning data points to the nearest cluster centroid and updating the centroids based on the mean of data points in each cluster.

**Usage**

You can explore the clustering results in the respective CSV files provided. Additionally, you can analyze and compare the performance of different clustering algorithms using the compared_results_iris.csv file.

**Dependencies**

Python 3.x,
Pandas,
NumPy,
Scikit-learn

**License**

This project is licensed under the MIT License - see the LICENSE file for details.
