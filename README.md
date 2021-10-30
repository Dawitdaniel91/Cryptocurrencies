# Cryptocurrencies

## Overview of Project

The purpose of this project is by using unsupervised learning skills to create an analysis for the clients who are preparing to get into the cryptocurrency market. Unsupervised learning is used for, how to process data, how to cluster, how to reduce dimensions, and how to reduce the principal components using PCA.

The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.

This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
During the analysis the following method is used:

. preprocessing the database,

. reducing the data dimension using Principal Component Analysis,

. clustering cryptocurrencies using K-Means,

. visualizing classification results with 2D and 3D scatter plots.

  
 #### Project outline
 
  . Deliverable 1: Preprocessing the Data for PCA
  
  . Deliverable 2: Reducing Data Dimensions Using PCA
  
  . Deliverable 3: Clustering Cryptocurrencies Using K-means
  
  . Deliverable 4: Visualizing Cryptocurrencies Results
  
## Resources
  
  . Data Source: crypto_data.csv, CryptoCompare

  . Software: Python, Anaconda Navigator , Conda , Jupyter Notebook 

## Results

### Deliverable 1: Preprocessing the Data for PCA

##### Table 1: create crypto_df DataFrame 
  
  ![image](https://user-images.githubusercontent.com/80365882/125846871-c5bf55bd-00c6-4927-8927-47e3e204b2ab.png)
  
### Deliverable 2: Reducing Data Dimensions Using PCA

 ##### Create a DataFrame with the three principal components

![image](https://user-images.githubusercontent.com/80365882/125849103-1d298042-1153-449d-8067-0515bce36c8d.png)

### Deliverable 3: Clustering Cryptocurrencies Using K-means

##### Clustering Cryptocurrencies using K-Means - Elbow Curve

elbow curve below using the K-Means method iterating on k values from 1 to 10

![image](https://user-images.githubusercontent.com/80365882/125848325-a415a5ee-7d84-4744-9650-38da2b1d6436.png)

### Deliverable 4: Visualizing Cryptocurrencies Results

##### Visualizing Cryptocurrencies

###### 3D-Scatter plot with clusters

![image](https://user-images.githubusercontent.com/80365882/125849757-783f2757-8b13-4197-9c16-73d57522583a.png)

The abouve 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

##### 2D-Scatter plot with clusters

![image](https://user-images.githubusercontent.com/80365882/125852997-3f5bed42-084d-43da-af53-db98a7aa2809.png)

##### Tradable Cryptocurrencies Table

##### Table 2: Tradable Cryptocurrencies 

![image](https://user-images.githubusercontent.com/80365882/125851487-17a2a6e7-43ce-48e5-bdfd-1c7ba21d7359.png)

Most of the cryptocurrencies are part of class #0 and #1.
The snapshot above shows that BitTorrent is the only cryptocurrency in class #2.

## Create a DataFrame with the two principal components

![image](https://user-images.githubusercontent.com/80365882/125852154-94c7aa5c-084c-4093-ab75-3e9733fa587d.png)

##### 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply

![image](https://user-images.githubusercontent.com/80365882/125852246-dab9dcd7-f6a9-430b-8f32-07f9090fabf3.png)

Plotting the scatter plot from two cryptocurrency features directly does not efficiently segregate the different classes. Then using the PCA algorithm is the right method for better visualizations.

## Summary

 532 cryptocurrencies classification identified based on similarities of their features




