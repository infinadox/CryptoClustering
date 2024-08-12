# Cryptocurrency Clustering

This project involves clustering cryptocurrencies based on their market data using K-Means and Principal Component Analysis (PCA). The objective is to identify the optimal number of clusters and compare the results with and without PCA.

## Project Overview

The project is divided into the following steps:

1. **Data Preparation**: 
   - Load and preprocess the cryptocurrency market data.
   - Normalize the data using `StandardScaler`.

2. **K-Means Clustering (Original Data)**:
   - Use the elbow method to determine the optimal number of clusters (`k`) for the original scaled data.
   - Apply K-Means clustering and visualize the clusters.

3. **Principal Component Analysis (PCA)**:
   - Reduce the dimensions of the data to three principal components using PCA.
   - Evaluate the explained variance of the PCA components.

4. **K-Means Clustering (PCA Data)**:
   - Repeat the K-Means clustering process on the PCA-reduced data.
   - Use the elbow method to determine the optimal number of clusters (`k`).
   - Visualize and compare the clustering results with the original data.

5. **Comparison and Analysis**:
   - Compare the elbow curves and clustering results of the original and PCA data.
   - Analyze the impact of reducing features using PCA.
