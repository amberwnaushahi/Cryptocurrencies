![image](https://blogs.lexisnexis.com/financial-crime-in-focus/wp-content/uploads/2020/05/crypto-blog-banner.jpg)

# Cryptocurrencies

## Background

This challenge uses unsupervised learning to analyze data on the cryptocurrencies traded on the market. The client Accountability Accounting are interested in offering a new cryptocurrencies investment portfolio to its customers. The company, however, is lost in the immense universe of cryptocurrencies. Thus, we implement the machine learning models to present a report of what cryptocurrencies are on the trading market and how cryptocurrencies could be grouped toward creating a classification for developing this new investment product.

The data we have is not ideal, so it has been processed to fit the machine learning models. Since there is no known output for what we are looking for, we decided to use unsupervised learning. To group the cryptocurrencies, we decided on a clustering algorithm to help the client with the new product offering.

## Technical Analysis

* Preprocessing the Data for PCA
* Reducing Data Dimensions Using PCA
* Clustering Cryptocurrencies Using K-means
* Visualizing Cryptocurrencies Results

## Visualizating the Results

Using Plotly Express and hvplot, we visualized the distinct groups that correspond to the three principal components created in the technical analysis and also created a table with all the currently tradable cryptocurrencies using the hvplot.table() function.

**a 3D scatter plot using Plotly Express to plot the clusters using the clustered_df DataFrame.**
This plot includes the following parameters on the plot: hover_name="CoinName" and hover_data=["Algorithm"] to show this additional info on each data point

![image](https://github.com/amberwnaushahi/Cryptocurrencies/blob/main/Resources/3d%20scatter%20clusters.PNG)

**A table using hvplot.table showing the tradable cryptocurrencies**

![image](https://github.com/amberwnaushahi/Cryptocurrencies/blob/main/Resources/table.PNG)

**A hvplot scatter plot where the X-axis is "TotalCoinsMined", the Y-axis is "TotalCoinSupply", the data is ordered by "Class", and it shows the CoinName when you hover over the data point**

![image](https://github.com/amberwnaushahi/Cryptocurrencies/blob/main/Resources/hvplot%20scatter.PNG)

