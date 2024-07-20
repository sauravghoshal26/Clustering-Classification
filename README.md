# Clustering Analysis on Training Data

## Table of Contents

- [Overview](#overview)
- [DBSCAN Clustering](#dbscan-clustering)
- [K-Means Clustering](#k-means-clustering)
- [Results](#results)
- [How to Use](#how-to-use)
- [Contributing](#contributing)

## Overview

This repository contains the results of clustering analysis performed on a training dataset using two clustering algorithms: DBSCAN and K-Means. The analysis includes the computation of Silhouette Scores and Adjusted Rand Index (ARI) for both clustering methods to evaluate their performance.

## DBSCAN Clustering

DBSCAN (Density-Based Spatial Clustering of Applications with Noise) is a clustering algorithm that groups together points that are closely packed together, while marking points that lie alone in low-density regions as outliers.

### Results
- **Silhouette Score for Training Data:** 0.4870027859962446
- **Adjusted Rand Index (ARI):** 0.2625285795589985

The Silhouette Score measures how similar an object is to its own cluster compared to other clusters. The ARI is a measure of the similarity between two data clusterings.

## K-Means Clustering

K-Means is a popular clustering algorithm that partitions the data into K distinct non-overlapping subgroups. It minimizes the sum of distances between the data points and their corresponding cluster centroids.

### Results
- **Silhouette Score for Training Data:** 0.606461845679642
- **Adjusted Rand Index (ARI):** 0.7492068431726737

The Silhouette Score and ARI for K-Means clustering indicate better performance compared to DBSCAN for this dataset.

## Results

| Clustering Algorithm | Silhouette Score       | Adjusted Rand Index (ARI) |
|----------------------|------------------------|---------------------------|
| DBSCAN               | 0.4870027859962446     | 0.2625285795589985        |
| K-Means              | 0.606461845679642      | 0.7492068431726737        |

Based on the results, K-Means clustering outperforms DBSCAN in terms of both Silhouette Score and Adjusted Rand Index for the given training dataset.

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/clustering-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd clustering-analysis
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the clustering analysis script:
    ```bash
    python clustering_analysis.py
    ```

## Contributing

Contributions are welcome! 
