# Crypto Market Data 

### Background
Created a unsupervised learning model to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. 

### Technologies Used 
- Jupyter Notebook
- Pandas
- Sklearn (KMeans, PCA, StandardScaler)

### Process 
- Prepare data using StandardScaler() from the scikit-learn to normalize the data from the CSV file 
- Find the Best Value of k Using the Original Scaled DataFrame and the elbow method
- Cluster the Cyptocurrencies with K-means using the original scaled data
- Optimize clusters with Principal Component Analysis (PCA) to reduce the features to three principal components.
- Find the Best Value for the k PCA Data
- Cluster Cryptocurrencies with K-means Using the PCA Data


### Analysis 
- Using fewer dimensions can reduced the complexity of the clustering process.
- In the K-Means plot, clusters rarely overlap, whereas in the PCA plot, they frequently overlap.
- Using fewer dimensions may also lead to loss of information. 
