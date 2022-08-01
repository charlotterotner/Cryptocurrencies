# Cryptocurrencies

## Deliverable 1: Preprocessing the Data for PCA
For this portion we read in the data file of cryptocurrencies and cleaned up our dataframe so no null values were included and so we only captured currencies that are being traded and that have a working algorithm. We also used the get_dummies feature to create variables for our text features. Lastly, we standardized the data using StandardScaler().


## Deliverable 2: Reducing Data Dimensions Using PCA
For this deliverable used PCA to reduce the dimensions to three principal components and created a new dataframe. 

## Deliverable 3: Clustering Cryptocurrencies Using K-means
For this deliverable we created an elbow curve to determine the best value to run our K-means model. The elbow curve flattened at 4, so we landed on 4 clusters. We then ran our k-means model and created a new dataframe that included our 3 principal compononents as well as the class for each cryptocurrency, that we got from running our kmeans prediction clusters. 

## Deliverable 4: Visualizing Cryptocurrencies Results
Lastly, we created a couple different visualizations. We created a 3d scatter plot that showed the 4 clusters, a table using hvplot, and lastly a scatterplot with TotalCoinsMoined and TotalCoinSupply. 
