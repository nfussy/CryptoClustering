# CryptoClustering

In this challenge, I used Python (via Jupyter Notebooks) and unsupervised machine learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

First, I scaled the original DataFrame in order to find the best value for k (number of clusters) and created an Elbow curve to determine this. After this, I clustered the cryptocurrencies accordingly.

Second, I optimized these clusters with PCA (Principal Component Analysis), roughly repeated the steps used to determine the optimal k-value, and clustered the optimized data accordingly.

ChatGPT was utilized in some of the hvplots to confirm the validity of the graph and to better convey the information.
