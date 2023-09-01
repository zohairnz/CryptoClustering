# CryptoClustering

This challenge centered around unsupervised machine learning. We used the k-means clustering and principal component analysis to reduce features.

We were provided data for a host of crypto currencies. We performed the following tasks:
1. Imported the data from a csv to dataframe and scaled it using the "StandardScalar" function
2. Created and plotted an elbow curve to determine the optimal value of k for our analysis
3. We fitted the original scaled data for k-means clustering and plotted the first two features while highlighting the predicted clusters
4. We used the PCA method to reduce the number of features and then fitted the scaled data
5. We again created and plotted an elbow curve to determine the optimal value of k for our analysis
6. We performed k-means clustering on the PCA data and created the same plots as described above
7. Compared the results of the two analysis
