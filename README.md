# UnSupervisedML_Homework
# Cryptocurrency Clusters

## Background

* Clustering algorithms are used to determine if the cryptocurrencies can be grouped together with other similar cryptocurrencies. 


### Data Preparation

* `crypto_data.csv` is read into Pandas. 

* Filtered the Cryptocurrencies that are being traded. 

* Removed all rows that have at least one null value.

* Filtered for cryptocurrencies that have been mined. Cryptocurrencies with out coins mined are discarded.

* Deleted  `CoinName`  column from the original dataframe.

* Converted the features with text values, `Algorithm` and `ProofType`, into numerical data. Used Pandas get_dummies() to create dummy variables. 

* Data is scaled using the StandardScaler().

### Dimensionality Reduction

* Dimentionality reduction is done with PCA.

### Cluster Analysis with k-Means

* Created an elbow plot to identify the best number of clusters. k is appears to be 5 from the elbow plot.

