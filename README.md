# CryptoClustering

# CryptoClustering

## Overview

This project focuses on clustering cryptocurrencies using unsupervised machine learning techniques such as K-Means and Principal Component Analysis (PCA). The goal is to identify patterns in cryptocurrency price changes over time and determine meaningful clusters using various feature combinations.

## Objectives

- Preprocess and normalize crypto market data.
- Use the Elbow Method to determine the optimal number of clusters.
- Apply K-Means clustering to both original and PCA-reduced datasets.
- Visualize clusters in 2D and 3D space using `hvPlot`.

## Files Included

- `Crypto_Clustering.ipynb` — Jupyter notebook containing all code and analysis.
- `crypto_market_data.csv` — Dataset containing cryptocurrency market information.
- `README.md` — Project overview and instructions.

## Visualization Tools

- `hvPlot` for interactive scatter plots.

-An HvPlot was used to plot the summary statistics of the df_market_data as below 
![alt text](<Screenshot 2025-05-08 at 1.10.02 PM.png>)
--An HvPlot was used to plot the crypto_market_predictions_df as below 
![alt text](<Screenshot 2025-05-08 at 1.13.32 PM.png>)


- Matplotlib for elbow curves.
-Matplotlib for elbow curves was used to plot a line chart with all the inertia values computed with as below ![alt text](<Screenshot 2025-05-08 at 1.15.47 PM.png>)
-Matplotlib for elbow curves was used to plot Composite plot to contrast the Elbow curves as shown ![alt text](<Screenshot 2025-05-08 at 1.19.19 PM.png>)

Concluion 
Despite of the Elbow Curves from the K-means and PCA are quite similar, using the PCA approach with fewer features to cluster the data it resulted in more easily-identifiable clusters than observed the ones used of K-means