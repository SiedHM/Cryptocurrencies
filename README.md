# Cryptocurrencies Project
Sied H Mohamed
# Overview of the project
A prominent investment bank is interested in providing offering a new cryptocurrency investment portfolio for its customers. Since there are large number of cryptocurrencies, the company is interested to have a report a report that includes what cryptocurrencies are on the trading market and create a cluster that enable the company to classify the new investment. 

Since there is no known cluster or classification, unsupervised machine learning algorithm is used to generate the clusters or classes. Before applying the machine learning algorism, I preprocess the database to remove missing values, convert strings to numeric and remove unnecessary columns. Following this I used Principal Component Analysis to reduce the dimension of the data set, and use the elbow curve and K-means algorism to produce the clusters. Finally, I used 2D and 3D plots to visualize the  findings. 

# Data Source
CSV data is obtained from [CreptoCompare](https://min-api.cryptocompare.com/data/all/coinlist)

# Method and software
Python 3.7 and Unspervised Machine Learning Algorithm

# Results
## Elbow Curve
![elbow-curve](https://github.com/SiedHM/Cryptocurrencies/blob/main/Images/elbow.png)

## Principal Components in 3D scatter plots
![3D](https://github.com/SiedHM/Cryptocurrencies/blob/main/Images/3D.png)

## Table of Tradable Crypto currencies
![currencies](https://github.com/SiedHM/Cryptocurrencies/blob/main/Images/Tradable%20currencies.png)

2D visualization of  Crypto currencies
![Crypto currencies](https://github.com/SiedHM/Cryptocurrencies/blob/main/Images/2D.png)

# Summary
Four clusters or classes of Crypto currencies are identifies and these can be used to classify investment opportunities for its customers.
