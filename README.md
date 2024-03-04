# Customer-and-Product-segmentation

This problem statement task is based on 

https://store.hbr.org/product/champo-carpets-improving-business-to-business-sales-using-machine-learning-algorithms/IMB879

The dataset file name is: Champo Carpets V1.csv

The dataset contains about 45 customers data. Each customer has one or more orders, and each order contains one or more items.
These customers are B2B customers.  Some of the item’s orders are expensive (or high value items) and some are not.

Objective:

Objectives of this task are:

-	Understand customers purchase behavior and segment them to understand their characteristics better.
-	Segment the products based on how customers buy them and segment them.
-	Understand how products are being bought together and cluster them together so that the clusters can become basis for recommendations.
Problem Description:

Exploratory Data Analysis

1.	Participants are expected to complete basic exploratory data analysis and find out at least 5 key insights from the data. 
2.	These could be univariate or bivariate analysis. 
3.	The insights should be depicted using appropriate charts.

Customer Segmentation

Stage 1:
Generate the following features based on customers purchase behavior.
-	frequency (number of orders) 
-	monetary value from the customers.
Creating clusters to segment customers based on above two features. Use appropriate methods to understand number of clusters and verify the quality of clusters.
Analyze each cluster and interpret them. Also, name each segment based on your understanding.

Stage 2:
Repeat the above exercise for all the three following algorithms and compare and interpret the results.

Stage 3:
Add some more features the above features using feature engineering for example kind of products customers are buying, high value or low value items bought, diversity of items (number of unique items bought) in orders.
Choose the right algorithms based on the understanding and complete the clustering exercises and infer if the clusters created have better understanding the customer segments or not.




Products Segmentation

Creating the following features for each of the products or items (item_id). 
-	total number quantities ordered.
-	total revenue generated.
-	number of customers orders the item.
-	average number of quantities per order and so on.
-	Add two more features based on your intuition or understanding.

Create clusters to segment items or products based on above two features. Use appropriate methods to understand number of clusters and verify the quality of clusters.
Analyze each cluster and interpret them. Also, name each segment based on your understanding.
Product Cluster Based on Purchase Patterns
Cluster the products based on how they are being bought together in orders. Choose the right metrics to cluster the products. 
Cluster the products or items in smaller sized clusters (min cluster size to be 2).
Display some of the clusters and discuss the results.
