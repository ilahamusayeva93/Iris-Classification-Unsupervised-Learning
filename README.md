# Iris Clustering Case Study

## Overview

In this case study, we explore clustering techniques on the Iris dataset using K-Means and Hierarchical Clustering. The dataset contains information about various features of iris flowers, and our goal is to identify natural groupings within the data.

## Dataset

The Iris dataset is loaded from the "iris.csv" file. The preprocessing steps include renaming columns, dropping unnecessary columns, handling missing values, removing duplicates, and scaling the features.

## K-Means Clustering

### Elbow Method
We use the Elbow method to determine the optimal number of clusters for K-Means. The Within-Cluster-Sum-of-Squares (WCSS) is calculated for different cluster numbers, and a plot is created to visualize the elbow point.

### K-Means Algorithm
K-Means clustering is performed with the chosen number of clusters. The resulting clusters are visualized on a scatter plot using the Sepal Length and Sepal Width features.

## Hierarchical Clustering

### Dendrogram
Hierarchical clustering is explored using a dendrogram. The Euclidean distances between data points are visualized to help choose the number of clusters.

### Agglomerative Clustering
Agglomerative Clustering is applied with the optimal number of clusters determined from the dendrogram. The resulting clusters are analyzed, and the mean values of the original features are computed for each cluster.

## Results and Visualization

The clustering results are visualized using scatter plots for both K-Means and Hierarchical Clustering. Additionally, mean feature values for each cluster are presented for Hierarchical Clustering.

## Conclusion

The case study demonstrates the application of clustering techniques to identify natural patterns in the Iris dataset. The insights gained from clustering can be valuable for further analysis and decision-making.

## Author

Ilaha Musayeva
09/29/23
