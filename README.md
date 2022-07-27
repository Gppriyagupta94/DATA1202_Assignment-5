# DATA1202_Assignment-5
**Project Title** 
Clustering 
**Description of the Project** 
We have collected data of cancer patients and using the Elbow and Silhouette methods of clustering we will optimize our K -means model to segment homogeneous symptoms found in one set of patients through all variables and differentiate them from heterogeneous symptoms found in other patients in order to further identify which patients can be treated using the similar medical treatment and which patients must be treated differently.
**Prerequisites and Installing**: 
Python (Anaconda) Install Procedure
Python Program Install
1) Go to the Anaconda website for downloads - https://www.anaconda.com/products/individual (the
Anaconda installers will be near the bottom of the page)
2) Download the appropriate latest version of Anaconda (64-bit graphical installer for Python 3.8 version)
3) After your install is complete, verify it by opening Anaconda Navigator:
From the start menu, select Anaconda3(64-bit), then select Anaconda
Navigator. If Navigator opens, you have successfully installed Anaconda.
4) Now close the Anaconda Navigator application
Python Libraries Install
5) Launch Command Prompt
Open the Anaconda Prompt (start menu under Anaconda3(64-bit))
6) Enter the following commands one at time and wait for each install to complete running.
 pip install plotly
 pip install imbalanced-learn
 pip install mlxtend
 pip install pandas-profiling
 pip install Boruta
7) Close the Anaconda Prompt/Terminal App
Final Step
Create a folder under Documents
**Running the Test**: 
To run the test the first step is to load the libraries:
1) Import pandas as pd
2) Import numpy as np
3) Import matplotlib as plt
Then we have to load the dataset 
To load the dataset we have given the csv file name
Once the dataset is loaded it will give you the first five rows of the dataset
Then we will drop the y variable that is 'Remiss' from the data set as we are not trying to predict a y value here
Then we will scale the data using sklearn standard scaler 
Now to determine the optimum number of clusters using k-means we will set the maximum iteration and inertia
In the first method that is Elbow Method 
1) We will select the range with plt.plot
2) We will give title to graph using plt.title
3) We will give number of clusters on x axis using plt.xlabel
4) We will calculate within cluster sum of squares on y axis usning plt.ylabel
5) To project graph we will use plt.show()
This will give us the graph of optimum number of clusters usning Elbow Method
We will now find optimum number of clusters by creating Silhouette Coefficients 
1) We will first define range of clusters in the kmeans 
2) To find silhoette coefficient we will use the metric - Euclidean
3) To plot the graph we will define range using plt.plot
4) To define the graph title we will use plt.title
5) To plot clusters on x axis we will use plt.xlable
6) To plot silhouette coefficient on y axis we will use plt.ylabel
7) To project graph we will use plt.show()
This will now project the silhouette coefficients and graph
The coeffiecient that is nearest to the value of 1 will project the optimum number of clusters on x axis
Now we will create Kmeans with 2 clusters to see how the data points will be projected in a scatter plot if we will only take 2 ckusters instaed of optimum nuber of clusters that we got through Elbow and Silhoette Method
1) We will add prediction to dataset that will divide the columns in 2 Clusters that Cluster 1 & 2
2) To plot the clusters in a scatter plot graph we will use plt.scatter
3) We will give two different colors to both clusters and a different color for the centroids in both the cluster
This will project the scatter plot graph of the dataset with two homogenous clusters
**Authors**
Professor Ade Oridate - Intial Work
**Acknowledgements**
The work is inspired by course 1200 week 9 Kmeans Model class


