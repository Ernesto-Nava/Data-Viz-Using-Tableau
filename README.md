# Data-Viz-Using-Tableau
My model and code for an assignment in which I was required to perform data formatting and decision tree and k-means clustering analysis in R and visualize my results through Tableau. 
# Data Formatting in R 
In order to accurately analyze and visualize the data set provided for this assignment, I pre-processed and formatted the data using R. 
The data formatting process included the following: 
identifying and replacing missing values with the mean value for the respective variable.
Creating new categorical variables.
Converting variable types (integer and character to factor, etc.). 
Removing redundant variables. 
# Decision Tree in R 
Using R, a decision tree model was built using the formatted data. The decision tree was built in order to calculate the misclassification rate and various ratios and identify the order of variable importance. 
# K-means Clustering in R 
The important variables identified in the decision tree are the variables that were the focus of my cluster analysis. 
Before integrating and running the cluster analysis in Tableau, the optimum number of clusters was identified by plotting an elbow chart. The number of clusters identified in my R analysis was then used in Tableau in order to integrate Tableau with R and to visualize the clusters. 
# Tableau Integration and Visualization 
Using the Rserve() function in R and creating parameters and a calculated field in Tableau, I integrated and established the connection between Tableau and R. After establishing the connection, I was able to visualize and analyze the data set through clusters. 
