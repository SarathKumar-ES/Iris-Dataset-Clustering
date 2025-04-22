# Iris-Dataset-Clustering
This project explores unsupervised learning techniques using the classic Iris dataset.We implement and compare KMeans and Hierarchical Clustering algorithms to identify natural groupings among the flower samples.

Dataset
Source: sklearn.datasets.load_iris()

Features: Sepal Length, Sepal Width, Petal Length, Petal Width

Target Removed: Species column dropped to perform clustering

Objectives
Apply KMeans and Hierarchical Clustering to identify clusters

Visualize cluster assignments

Compare performance and patterns found by each method

Algorithms Used
KMeans Clustering: Partitions data into k distinct, non-overlapping subsets.

Hierarchical Clustering: Builds a nested tree of clusters via bottom-up approach (Agglomerative).

Visualizations
Cluster scatter plots for both KMeans and Hierarchical Clustering

Dendrogram for cluster hierarchy analysis

Key Results
Both clustering methods successfully grouped data into meaningful clusters.

Visual comparison shows high similarity to actual species groups.

Dendrogram provided intuitive insight into data structure.

Conclusion
Unsupervised clustering algorithms effectively captured the natural structure of the Iris dataset. KMeans produced distinct clusters, while Hierarchical Clustering allowed deeper insights through dendrograms.

