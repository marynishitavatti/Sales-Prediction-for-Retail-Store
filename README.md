# Customer Segmentation Using Clustering

## Overview

Customer segmentation is an important technique used by businesses to group customers based on similar characteristics and purchasing behavior. This project applies the **K-Means Clustering** algorithm to divide customers into meaningful groups using demographic and spending information.

The project uses the **Mall Customer Segmentation** dataset from Kaggle, which contains customer details such as **Age**, **Gender**, **Annual Income**, and **Spending Score**. By identifying different customer segments, businesses can better understand customer behavior and design targeted marketing strategies.

This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature selection, determining the optimal number of clusters using the **Elbow Method**, training the K-Means clustering model, visualizing customer segments, and interpreting the clustering results.

---

## Objectives

- Analyze customer demographic and spending data.
- Perform data cleaning and preprocessing.
- Explore relationships between customer features using visualization.
- Determine the optimal number of clusters using the Elbow Method.
- Apply the K-Means Clustering algorithm.
- Visualize customer groups.
- Interpret the characteristics of each customer segment.

---

## Dataset

**Dataset Name:** Mall Customer Segmentation Data

**Source:** Kaggle

https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

**Features**
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Algorithm

- K-Means Clustering
- Elbow Method

---

## Project Workflow

1. Import required libraries.
2. Load the customer dataset.
3. Perform data preprocessing.
4. Conduct Exploratory Data Analysis (EDA).
5. Select relevant features for clustering.
6. Determine the optimal number of clusters using the Elbow Method.
7. Train the K-Means clustering model.
8. Visualize customer segments.
9. Interpret the clustering results.

---

## Project Structure

```
Customer-Segmentation-Using-Clustering/
│
├── README.md
├── Customer_Segmentation_using_Clustering.ipynb
└── Mall_Customers.csv
```

---

## Results

The K-Means algorithm successfully groups customers into different clusters based on annual income and spending score. These customer segments help businesses understand purchasing patterns and support data-driven marketing strategies such as personalized promotions, customer targeting, and retention planning.

Author
Mary Nishita Vatti
