We aim to transform the transactional data into a customer-centric dataset by creating new features that will facilitate the segmentation of customers into distinct groups using the K-means clustering algorithm. This segmentation will allow us to understand the distinct profiles and preferences of different customer groups.

Objectives:
Data Cleaning & Transformation: Clean the dataset by handling missing values, duplicates, and outliers, preparing it for effective clustering.
Feature Engineering: Develop new features based on the transactional data to create a customer-centric dataset, setting the foundation for customer segmentation.
Data Preprocessing: Undertake feature scaling and dimensionality reduction to streamline the data, enhancing the efficiency of the clustering process.
Customer Segmentation using K-Means Clustering: Segment customers into distinct groups using K-means, facilitating targeted marketing and personalized strategies.
Cluster Analysis & Evaluation: Analyze and profile each cluster to develop targeted marketing strategies and assess the quality of the clusters formed.

In this project, I used Machine Learning to segment customers based on their purchasing behavior with the KMeans clustering algorithm. The goal was to identify patterns in customer data and classify them into meaningful segments for targeted strategies.
Here’s a quick breakdown of the approach I followed:
1. Data Collection: I used retail transaction data from the UCI Machine Learning Repository.
2. Preprocessing: Cleaned and transformed the data, handled missing values, and dealt with outliers. After that, I standardized the features through scaling.
3. Clustering: I applied the KMeans clustering algorithm to group customers into 3 distinct segments, based on their RFM model (Recency, Frequency, and Monetary value):
Recency: How recent was the customer’s last transaction?
Frequency: How often does the customer make a purchase?
Monetary value: How much has the customer spent in total?
4. Visualization: I visualized the segmentation using box plots, elbow curves, and cluster snapshots to better interpret the patterns within each group.

 
