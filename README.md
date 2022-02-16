# Cryptocurrency Clusters

## Background
Here, unsupervised machine learning is used to explore whether the cryptocurrencies, from a set of raw data, can be grouped together with other similar cryptocurrencies.

The dataset was obtained from [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist).

After cleaning and converting all data to a numeric form with dummy variables, the data was scaled. 

Then PCA dimensionality reduction was performed, with 90% of the explained variance preseved.

Next, the principal components dataset was further reduced with t-SNE. 

An elbow plot, generated from a k-means clustering of the t-SNE data, is used to show that the cryptocurrencies can be grouped into 4 clusters. 

- - -

## References

Crypto Coin Comparison Ltd. (2020) Coin market capitalization lists of crypto currencies and prices. Retrieved from [https://www.cryptocompare.com/coins/list/all/USD/1](https://www.cryptocompare.com/coins/list/all/USD/1)
