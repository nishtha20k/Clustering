# Clustering with PyCaret

## Overview

This project demonstrates how to perform clustering using PyCaret, a versatile Python library for automating machine learning workflows. Clustering involves grouping similar data points together based on certain characteristics. PyCaret simplifies the process of building and evaluating clustering models, allowing for rapid experimentation and model selection.

## Installation

To run this project, you'll need to have Python installed on your system. You can install PyCaret and other required dependencies using pip:

 sh
pip install pycaret


## Details

In this project, clustering was performed using different clustering techniques on Dataset 'Iris':

1. *KMeans Clustering*: KMeans clustering is a popular method for partitioning a dataset into K clusters.
   
2. *Agglomerative Clustering*: Agglomerative clustering is a hierarchical clustering technique that recursively merges the nearest pairs of clusters.
   
3. *KMeanShift Clustering*: KMeanShift clustering is a density-based clustering algorithm that doesn't require specifying the number of clusters beforehand.

For each clustering technique, the following configurations were experimented with:

- *Cluster Sizes*: 3, 4, 5
- *Data Processing Techniques*:
  - No Data Processing
  - Normalization
  - Transformation
  - PCA (Principal Component Analysis)
  - T + N (Transformation + Normalization)
  - T + N + PCA (Transformation + Normalization + PCA)
