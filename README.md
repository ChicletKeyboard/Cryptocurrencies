# Cryptocurrencies

This project was created to be a report that includes the types of cryptocurrencies on the trading market and a classification system to group the currencies for cliente investment portfolios. Since the output is unknown, the most appropriate model to create the analysis would be unsupervised learning and clustering algorithms to group the currencies.

Includes steps for:
1) Preprocessing PCA data from crypto_data.csv file.
2) Reducing data dimensions using PCA to 3 principal components and placed into new DataFrame.
3) Clustering cryptocurrencies using K-means algorithm. Create elbow curve using hvplot library, best value for K from the pcs_df DataFrame, and then run algorithm to predict K clusters for data.
