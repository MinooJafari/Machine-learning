# K-Means Clustering

## Project Overview
This project demonstrates the K-Means Clustering algorithm, an unsupervised machine learning technique used to group similar data points into clusters.

Using Python and Scikit-learn, the project generates a synthetic dataset containing 400 data points distributed across four clusters. The K-Means algorithm identifies these groups and determines their corresponding cluster centers.

## Technologies & Libraries
- Python
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Key Concepts
- Unsupervised Machine Learning
- K-Means Clustering
- Data Generation
- Data Visualization
- Cluster Centers (Centroids)
- Data Segmentation

## Project Workflow
1. Generate a synthetic dataset using `make_blobs`.
2. Visualize the original data points.
3. Apply the K-Means clustering algorithm.
4. Predict cluster labels for each data point.
5. Calculate cluster centers (centroids).
6. Visualize the predicted clusters using different color maps.
7. Compare the original labels with the predicted clusters.

## Algorithm
K-Means is an unsupervised learning algorithm that divides data into a predefined number of clusters based on similarities between data points.

In this project, the algorithm is configured with four clusters (`n_clusters=4`).

## Results
The model successfully identifies four clusters within the generated dataset and visualizes them using different colors. The cluster centers are also displayed to demonstrate the position of each centroid.

## Learning Objectives
- Understand how K-Means clustering works.
- Learn how to implement clustering using Scikit-learn.
- Understand the role of centroids in clustering.
- Practice visualizing machine learning results.
- Compare actual cluster labels with predicted cluster assignments.
