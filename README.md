# CryptoClustering Cluerting Analysis
Overview
This repository contains a Python script that performs a clustering analysis on a dataset of cryptocurrency market data. The script uses K-Means clustering and Principal Component Analysis (PCA) to identify patterns and groupings in the data.

# Dataset
The dataset used in this analysis is a CSV file containing market data for various cryptocurrencies. The data includes features such as price change percentages over different time periods (e.g. 24 hours, 7 days, etc.).

# Script Overview
The script is divided into several sections:

# Data Preparation: The script loads the dataset, scales the data using StandardScaler, and creates a copy of the original data.
K-Means Clustering (Original Data): The script performs K-Means clustering on the original data, using the Elbow method to determine the optimal number of clusters (k).
K-Means Clustering (PCA Data): The script applies PCA to the original data, reducing the dimensionality to 3 principal components. It then performs K-Means clustering on the PCA data, again using the Elbow method to determine the optimal number of clusters (k).
Visualization: The script creates scatter plots to visualize the clustering results for both the original data and the PCA data.

# Dependencies
The script requires the following Python libraries:

pandas
hvplot
scikit-learn (specifically, KMeans and PCA)


# Running the Script
To run the script, simply execute the Python file in a terminal or command prompt. The script will output the clustering results and visualizations to the console.

# Results
The script outputs several results, including:

The optimal number of clusters (k) for both the original data and the PCA data
Scatter plots visualizing the clustering results for both datasets
A composite plot comparing the Elbow curves for both datasets
A composite plot comparing the clustering results for both datasets
