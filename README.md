# KMeans-Cluster-Analysis

[![](https://img.shields.io/badge/Python-blue?style=for-the-badge)](https://github.com/hamzamohdzubair/redant)
[![](https://img.shields.io/badge/ML-KMeans-blueviolet?style=for-the-badge)](https://hamzamohdzubair.github.io/redant/)
[![](https://img.shields.io/badge/Library-Scikitlearn-yellow?style=for-the-badge)](https://docs.rs/crate/redant/latest)
[![](https://img.shields.io/badge/Package-Yellowbrick-orange?style=for-the-badge)](https://crates.io/crates/redant)

![](https://img.shields.io/static/v1?label=&message=KElbowVisualizer&color=green)
![](https://img.shields.io/static/v1?label=&message=SilhoutteVisualizer&color=blue)


Identifying specific groups in the customer base with K-Means clustering allows us to connect patterns between data elements without labels attached to them. Once these structures are discovered, we can make more informed decisions about our customers.


## Research Question

Can we identify specific groups with patterns in our customer base using the K-Means Clustering method?

## The Goal of the Data Analysis

By Identifying specific groups in the customer base, we will be able to identify and define patterns among customers. This information will allow us to formulate deeper analyses and predictions for customer churn.

## Technique Justification

Clustering allows the identification of patterns between data elements without any labels attached to them. Revealing these patterns helps discover structures in the data that were not obvious before. Once these structures are discovered, making informed decisions become easier.
The clustering technique I used was K-Means clustering. K-Means is an unsupervised clustering algorithm that can be used to quickly cluster large datasets. The algorithm initially assigns any k centroids. Then, iteratively, assigns the points to clusters based on the distance between the points and the centroids until all data points are assigned to a cluster. These clusters can then be put back into the dataset to reveal insights.

## Elbow Method

The Elbow Method helps to choose the optimum number of clusters by fitting the model with a range of values for _k_. The chart indicates the best fit at the "elbow" point as shown in the example below.

![image](https://github.com/secil-carver/KMeans-Cluster-Analysis/assets/77639654/ad692daa-c437-4b75-acd3-01277c7023a8)

## Silhouette Method

Visual interpretation of clusters of data. It provides graphical validation of how well each object is classified. The score assigned determines how well each object lies in its cluster. A high average silhouette indicates good clustering. Numbers close to zero indicate the object lies in the decision boundary between two clusters.

![image](https://github.com/secil-carver/KMeans-Cluster-Analysis/assets/77639654/535e631e-8c98-4b50-93a7-03b15573a7f1)

