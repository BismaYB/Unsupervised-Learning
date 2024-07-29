# Unsupervised-Learning

This repository contains the code and analysis for the clustering assignment using the Iris dataset.

## Dataset

The Iris dataset from the sklearn library is used for this assessment.

## Contents

Unsupervised learning.ipynb: Jupyter Notebook with the clustering implementation and visualizations.

README.md: This file.

## 1. Loading and Preprocessing 

The Iris dataset is loaded from the sklearn library and the species column is dropped as this is a clustering problem.

## 2. Clustering Algorithm Implementation 

 ### A) KMeans Clustering 
 
KMeans clustering partitions the dataset into K clusters by minimizing the distance between data points and their corresponding cluster centroids. The algorithm iteratively updates the centroids and reassigns data points to the nearest centroid until convergence.

Suitability for the Iris Dataset
KMeans is suitable for the Iris dataset because it can effectively separate the data into clusters based on the features provided.

#### KMeans Clustering Analysis

Cluster Centroids: KMeans identified three clusters with centroids representing the average feature values for each cluster.
Visualization: The scatter plot shows distinct clusters with minimal overlap, indicating KMeans effectively grouped the data.


### B) Hierarchical Clustering

KMeans clustering partitions the dataset into K clusters by minimizing the distance between data points and their corresponding cluster centroids. The algorithm iteratively updates the centroids and reassigns data points to the nearest centroid until convergence.

Suitability for the Iris Dataset
KMeans is suitable for the Iris dataset because it can effectively separate the data into clusters based on the features provided.

#### Hierarchical Clustering Analysis

Dendrogram: The dendrogram provides a visual representation of the hierarchical structure. By truncating the dendrogram, we focused on the most significant merges, providing a clear view of the data’s clustering structure.
Cluster Assignment: Hierarchical clustering also identified three clusters, and the scatter plot shows a similar clustering pattern to KMeans.

### Comparison

Both KMeans and hierarchical clustering identified three clusters in the Iris dataset. The cluster assignments and visualizations are similar, indicating both methods are suitable for this dataset.
KMeans is computationally faster and well-suited for larger datasets, while hierarchical clustering provides a detailed view of the clustering structure, which can be useful for understanding data relationships.

## Conclusion

This assignment demonstrates the application of KMeans and hierarchical clustering techniques to the Iris dataset. Both methods effectively grouped the data into clusters, with visualizations providing insights into the clustering patterns.

### Author

Bisma yb

