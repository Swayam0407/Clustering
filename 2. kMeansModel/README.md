# Project Name

[License](LICENSE.md) | [Contributing](CONTRIBUTING.md)

## Overview
... content here ...


# Pre-Requisites: Clustering Evaluation Metrics

## Silhouette Score (Range: -1 to 1)
- **Higher is better**.
- Measures how similar each point is to its own cluster compared to other clusters.
- A value close to **1** indicates that points are well-matched within their cluster and poorly matched with other clusters.

## Calinski-Harabasz Index (No upper bound, higher is better)
- **Higher is better**.
- Considers the ratio of the sum of between-cluster dispersion to within-cluster dispersion.
- A **higher value** indicates well-defined and separated clusters.

## Davies-Bouldin Index (Range: 0 to ∞, lower is better)
- **Lower is better**.
- Measures the average similarity ratio between each cluster and its most similar cluster.
- A **lower score** indicates better separation between clusters.

## Summary of Desired Metrics
- **Silhouette Score**: Higher values indicate well-separated clusters.
- **Calinski-Harabasz Index**: Higher values suggest strong clustering structure.
- **Davies-Bouldin Index**: Lower values mean clusters are distinct and less similar.
