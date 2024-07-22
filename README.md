# CryptoClustering

This project applies machine learning techniques to cluster cryptocurrencies based on various performance metrics. Principal Component Analysis (PCA) is used for reducing the dimensionality of the data, and KMeans clustering is used for grouping the cryptocurrencies. I was provided assistance by Sean Morey, the instructor of the class. Nomsa Tsotetsi, a BCS tutor, was a big help. I lastly could not have been able to finish this code without the help from the BCS Xpert Learning Assistant.

## Introduction

Cryptocurrencies have gained significant attention in recent years, and their performance metrics can provide insights into market trends. This project aims to cluster cryptocurrencies using PCA and KMeans clustering to identify patterns and group similar cryptocurrencies together.

## Results

#### Clustering

The KMeans clustering identified distinct groups of cryptocurrencies based on their performance metrics. The elbow method was used to determine the optimal number of clusters was 4.

#### PCA Weights

The PCA analysis identified the following features as having the strongest influence on each principal component:

* PCA1:

    - Strongest Positive: price_change_percentage_1y
    - Strongest Negative: price_change_percentage_24h

* PCA2:

    - Strongest Positive: price_change_percentage_30d
    - Strongest Negative: price_change_percentage_1y

* PCA3:

    - Strongest Positive: price_change_percentage_7d
    - Strongest Negative: price_change_percentage_60d