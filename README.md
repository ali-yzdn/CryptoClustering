# Cryptocurrency Clustering Analysis

## Overview
This project aims to analyze cryptocurrency market data using unsupervised learning techniques, specifically K-Means clustering and Principal Component Analysis (PCA). The goal is to understand patterns and relationships among cryptocurrencies based on their price change percentages over 24 hours and 7 days.

## Dataset
The dataset `crypto_market_data.csv` contains information about various cryptocurrencies, including their price change percentages over 24 hours and 7 days.

## File Structure
- `crypto_market_data.csv`: Dataset containing cryptocurrency market data.
- `cryptocurrency_clustering.ipynb`: Jupyter Notebook containing the Python code for data analysis and clustering.
- `README.md`: This file, providing an overview of the project.

## Analysis Steps
1. Load the dataset and inspect its summary statistics.
2. Normalize the data using StandardScaler.
3. Use the elbow method to find the optimal number of clusters (k) for both the original scaled data and PCA-transformed data.
4. Cluster the cryptocurrencies using K-Means for the best value of k for both datasets.
5. Visualize the clustering results using scatter plots.
6. Perform PCA on the original scaled data and analyze the explained variance.
7. Cluster the cryptocurrencies using K-Means for the best value of k for PCA-transformed data.
8. Visualize the clustering results after PCA transformation.
