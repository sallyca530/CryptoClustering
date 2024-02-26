# CryptoClustering

### Cryptocurrency Price Change Pattern Categorization
#### Overview
In this repository, I leveraged Python and unsupervised machine learning techniques to categorize and group cryptocurrencies based on their historical price change patterns. The goal was to identify similarities in price trends among various cryptocurrencies.

#### Key Steps
* Data Preparation:

Processed and prepared the data for analysis.
Utilized StandardScaler for data normalization to ensure uniformity in the dataset.

* Determining Optimal k for K-means:

Found the best value for k using the original scaled DataFrame.
Applied the K-means algorithm to cluster cryptocurrencies based on their original scaled data.

* Optimizing Clusters with Principal Component Analysis (PCA):

Implemented Principal Component Analysis to reduce the dimensionality of the data.
Optimized clusters based on the PCA-transformed data.

* Refining k Using PCA Data:

Identified the best value for k using the PCA-transformed data.
Employed K-means clustering on cryptocurrencies using the PCA-transformed data.