# CryptoClustering-challenge
CryptoClustering-challenge
### The CryptoClustering-challenge uses unsupervised machine learning in order to analyze the impact generated by 24 hour or 7 day price changes on cryptocurrencies.
#### The use of scikit-learn was fundamental to apply the data analysis for example finding the best value for k, cluster analysis and Principal component analysis.
#### 1. from sklearn.cluster import KMeans was used in the analysis to find the best value for k in the elbow curve plot
#### 2.from sklearn.decomposition import PCA was used to run the Principal Component Analysis and reduce to principal features
#### 3.from sklearn.preprocessing import StandardScaler was used to normalize the data and ensure equal value is given to each feature when calculating K-means algorithms in the scaled dataframe
#### The use of hvplot.pandas was implemented in order to visualize the analyzed data directly from the data frames. It also allowed to interact with the visaulizations to better do the comparative analysis of how PCA analysis affected the overall visualized data. 
##### Xpert Learning Assitant was used to fix a syntaxis error in the first for loop to find the best k value 
##### It was also used to fix a syntaxis error on the PCA cluster plot
