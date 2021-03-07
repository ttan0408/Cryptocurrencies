# Cryptocurrencies

## Objective
Martha is asking us to work on project where we will help her Team at Accoutability Accounting to perform an analysis on cryptocurrency investments. We will have to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Preprocessing the Data for Principal Component Analysis(PCA)
The data set we have is raw data with numperous of missing, and unusable values. We have to perform a clean up in order to be apply machine learning algorithm for the analysis. After cleaning up we were able to put them into new data frame and are ready for use. Dataframe is shown as below :

Clean_DataFrame_for_Cluster_Analysis  : 
 ![alt text][Image1]
  
 [Image1]: https://github.com/ttan0408/Credit_Risk_Analysis/blob/main/Resources/Naive_Random_Oversampling.PNG "Clean_DataFrame_for_Cluster_Analysis"

## Reducing Data Dimensions Using PCA
We have to transform data into a smaller dimension in order to speed up machine learning algorithms. Principle Component Analysis is a statistical technique that we will use in this step. PCA reduces the number of dimensions by transforming a large set of variables into a smaller one that contains most of the information in the original large set. The new dataframe after dimension reduction is shown below :

DataFrame_for_Principle_Components  : 
 ![alt text][Image2]
  
 [Image2]: https://github.com/ttan0408/Credit_Risk_Analysis/blob/main/Resources/Naive_Random_Oversampling.PNG "DataFrame_for_Principle_Components"

## Clustering Cryptocurrencies Using K-means
K-means is an unsupervised learning algorithm used to identify and solve clustering issues. Firts we calculate the inertia for the range of K values then we create the elbow curve to determine how many clusters we like to use in K-Means model. The elbow curve show K = 4 is where the slope change significant which means we will have 4 cluster for K-Means model. The new DataFrame including predicted clusters and cryptocurrencies features are shown below :

DataFrame_for_Predict_Future_Currency  : 
 ![alt text][Image3]
  
 [Image3]: https://github.com/ttan0408/Credit_Risk_Analysis/blob/main/Resources/Naive_Random_Oversampling.PNG "DataFrame_for_Predict_Future_Currency"

## Visualizing Cryptocurrencies Results
Finally, we visualize the plot between TotalCoinSupply "Y", vs. TotalCoinsMined "X". The plot is shown below :

Plot_TotalCoinSupply_TotalCoinsMined  : 
 ![alt text][Image4]
  
 [Image4]: https://github.com/ttan0408/Credit_Risk_Analysis/blob/main/Resources/Naive_Random_Oversampling.PNG "Plot_TotalCoinSupply_TotalCoinsMined"

