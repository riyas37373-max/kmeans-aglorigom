# K-Means Clustering from Scratch (NumPy)

This repository implements the K-Means clustering algorithm **from scratch** using only NumPy for the core logic. The goal is to understand unsupervised learning, distance metrics, and the Elbow method without relying on scikit-learn's `KMeans`.

## Project Overview

- Generate a synthetic dataset of 500 points with 4 clusters using `sklearn.datasets.make_blobs`.
- Implement K-Means:
  - Centroid initialization (random selection)
  - Assignment step (nearest centroid)
  - Update step (mean of assigned points)
  - Inertia (Within-Cluster Sum of Squares)
- Apply the Elbow method for K = 1 to 10.
- Run final K-Means with the chosen K and report centroids & final inertia.

## Repository Structure

- `src/data_generation.py` – synthetic data creation
- `src/kmeans_scratch.py` – K-Means implementation (NumPy only)
- `src/elbow_method.py` – Elbow method loop and logging
- `notebooks/kmeans_demo.ipynb` – optional visualization / experiments

## How to Run

