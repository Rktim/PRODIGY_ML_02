# PRODIGY_ML_02

# Mall Customers Clustering Project

## Project Overview

This project aims to segment mall customers based on their annual income and spending score using K-means clustering. By understanding these segments, mall management can develop targeted marketing strategies to enhance customer satisfaction and increase revenue.

## Steps

### 1. Data Loading and Exploration

- The dataset containing information about mall customers was loaded using pandas.
  
- The head and tail of the dataset were displayed to get a glimpse of the data.
  
- Basic information about the data, including data types and missing values, was obtained using `data.info()` and `data.isnull().sum()`.
  
- The distribution of annual income and spending score was visualized using histograms.

### 2. Data Preprocessing

- The annual income and spending score columns were extracted into a separate DataFrame.
  
- A pairplot was created to visualize the relationship between these two variables.
  
- The data was standardized using `StandardScaler` to ensure that all features have the same scale.

### 3. Applying K-means Clustering

- The elbow method was used to determine the optimal number of clusters by calculating the inertia for different cluster numbers.
  
- Based on the elbow method, a KMeans model with 5 clusters was chosen.
  
- The model was fit to the scaled data, and cluster labels were assigned to each data point.

### 4. Visualizing Clusters

- A scatter plot was created to visualize the clusters based on annual income and spending score.
  
- Boxplots were created to visualize the distribution of annual income and spending score within each cluster.

## Discussion

- The K-means clustering analysis successfully identified five distinct clusters of customers based on their annual income and spending score.
  
- The analysis revealed that clusters 0 and 4 represent customers with high spending scores, while clusters 1, 2, and 3 represent customers with lower spending scores.
  
- The analysis also showed that customers in cluster 0 have the highest annual income, while customers in clusters 2 and 3 have the lowest annual income.
  
- This information can be used by mall management to develop targeted marketing strategies for each cluster. For example, the mall could offer discounts or promotions to customers in clusters 1, 2, and 3 to encourage them to spend more.


## Conclusion

By segmenting customers into distinct clusters, the mall can tailor its marketing efforts to better meet the needs of different customer groups. This targeted approach can lead to increased customer satisfaction and higher sales.

