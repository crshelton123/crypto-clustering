# Crypto Clustering
* For this assignment we were looking at cryptocurrency market data. 
* I began by importing necessary libraries and reading in the csv data. 
* Then I ran a KMeans cluster analysis on the data and created an elbow curve, which shows 4 clusters as the best option.  
![Elbow Curve](Resources/df_elbow_plot.png)
* I also created a scatter plot of the data to visually see the clusters. 
![Data Scatter Plot](Resources/crypto_data_plot.png)
* Next I ran a Principal Component Analysis on the data and included 3 PCAs. 
* The PCA dataframe was then analyzed via KMeans again to reveal 4 clusters were still best. 
![PCA Elbow Curve](Resources/pca_elbow_plot.png)
* PCA data was visualized on a scatter plot. 
![PCA Scatter Plot](Resources/crypto_pca_plot.png)
* Based on the results, the integrity of the data is not lost by running PCA. With both the datasets the optimal value of k is 4, meaning there are 4 distinct groupings to encompass the data. Also, in both scatter plots it is evident that "Ethlend" and "Celcius-degree-token" are each their own clusters. 