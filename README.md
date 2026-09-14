# Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project demonstrates **Unsupervised Machine Learning** using the **K-Means Clustering algorithm**.

The goal is to segment mall customers into different groups based on their **Annual Income** and **Spending Score**. This can help businesses understand customer behavior and identify different customer segments.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

## 📊 Dataset

The project uses the **Mall Customers dataset**.

The main features used for clustering are:

* Annual Income (k$)
* Spending Score (1-100)

Other customer information such as Age and CustomerID is also used for analyzing the resulting clusters.

## 🔍 Project Steps

1. Import the required Python libraries
2. Load the Mall Customers dataset
3. Explore the dataset
4. Check the dataset shape
5. Check for missing values
6. Generate descriptive statistics
7. Select features for clustering
8. Standardize the selected features using `StandardScaler`
9. Calculate WCSS for different values of K
10. Use the Elbow Method to determine the number of clusters
11. Apply K-Means clustering with K = 5
12. Assign cluster labels to customers
13. Visualize the customer clusters
14. Create a cluster summary
15. Analyze the characteristics of each customer segment

## 🤖 Machine Learning Algorithm

### K-Means Clustering

K-Means is an **unsupervised machine learning algorithm** that groups similar data points into clusters.

In this project, K-Means is used to group customers according to their annual income and spending score.

## 📈 Elbow Method

The **Elbow Method** is used to help select an appropriate number of clusters.

WCSS (Within-Cluster Sum of Squares) is calculated for K values from 1 to 10. The resulting values are visualized using an elbow graph.

## 📌 Final Model

The project applies:

```python
KMeans(n_clusters=5, random_state=7)
```

The customers are divided into **5 clusters**.

## 📊 Cluster Analysis

After clustering, the project creates a summary containing:

* Average Age
* Average Annual Income
* Average Spending Score
* Number of Customers

This helps understand the characteristics of each customer segment.

## 🎯 Objective

The main objective of this project is to understand how **unsupervised machine learning** can be used for **customer segmentation** and business analysis.

## 👩‍💻 Author

**Ranjitha D K**
