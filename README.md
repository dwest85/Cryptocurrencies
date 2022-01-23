# Cryptocurrencies

# Description
* The purpose of this analysis was to gain insight into the groupings of different cryptocurrencies using clustering and reducing down the data with PCA. After determining the proper amount of cluster groups using an elbow curve. We processed the data and determined that most cryptocurrencies fell within the first two groups. The sole currency BitTorrent fell into the third grouping, which was treated as more of an outlier. 

# Elbow Curve
* We determined the necessary cluster grouping by looping through the KMeans algorithm using a list of clusters and fitting our PCA data. The Elbow Curve visualization showed us that the curve was most aggressive at 4 clusters, giving using the necessary amount to fit to our model.
![elbowcurve](https://github.com/dwest85/Cryptocurrencies/blob/main/markdownpics/elbowcurve.PNG)

# Prediction Array
* Fitting this to our PCA data gave the necessary array to use for our cluster groupings.
![array](https://github.com/dwest85/Cryptocurrencies/blob/main/markdownpics/array.PNG)

# Creating our final database
* We concatanated the CoinName data paired with our model array labels under the Class column. Did created the necessary table for our groupings. 
![cluster](https://github.com/dwest85/Cryptocurrencies/blob/main/markdownpics/cluster.PNG)

# 3d Visualization of the cluster grouping predictions
![3d](https://github.com/dwest85/Cryptocurrencies/blob/main/markdownpics/3d.PNG)

# HVPLOT Table
![hvplot](https://github.com/dwest85/Cryptocurrencies/blob/main/markdownpics/hvplot.PNG)

# 2d Scatter plot showing the four classes
![2d](https://github.com/dwest85/Cryptocurrencies/blob/main/markdownpics/2d.PNG)
