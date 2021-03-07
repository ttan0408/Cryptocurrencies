# Cryptocurrencies

## Objective
Martha is asking us to work on project where we will help her Team at Accoutability Accounting to perform an analysis on cryptocurrency investments. We will have to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Preprocessing the Data for Principal Component Analysis(PCA)
The data set we have is raw data with numperous of missing, and unusable values. We have to perform a clean up in order to be apply machine learning algorithm for the analysis. After cleaning up we were able to put them into new data frame and are ready for use. Dataframe is shown as below :

## Reducing Data Dimensions Using PCA
We have to transform data into a smaller dimension in order to speed up machine learning algorithms. Principle Component Analysis is a statistical technique that we will use in this step. PCA reduces the number of dimensions by transforming a large set of variables into a smaller one that contains most of the information in the original large set. The new dataframe after dimension reduction is shown below :


## Clustering Cryptocurrencies Using K-means
K-means is an unsupervised learning algorithm used to identify and solve clustering issues. Firts we calculate the inertia for the range of K values then we create the elbow curve to determine how many clusters we like to use in K-Means model. The elbow curve show K = 4 is where the slope change significant which means we will have 4 cluster for K-Means model. The new DataFrame including predicted clusters and cryptocurrencies features are shown below :



## Visualizing Cryptocurrencies Results
Finally, we visualize the plot between TotalCoinSupply "Y", vs. TotalCoinsMined "X". The plot is shown below :
