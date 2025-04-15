# Customer Segmentation Using K-Means Clustering

This project demonstrates customer segmentation using K-Means clustering on the popular Mall Customers dataset. The goal is to group customers based on their Annual Income and Spending Score.

## Dataset

The dataset `Mall_Customers.csv` contains the following columns:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

## Objective

The main objective is to identify distinct customer groups using **K-Means Clustering**, enabling targeted marketing strategies.

## Techniques Used

- Exploratory Data Analysis (EDA)
- Data visualization with **Seaborn** and **Matplotlib**
- Elbow method to determine optimal number of clusters
- K-Means clustering from **scikit-learn**

## Sample Plots

### Elbow Plot
Used to find the optimal number of clusters:

![Elbow Plot](link-to-image-if-you-upload-one)

### Cluster Visualization
Colored scatter plot showing customer segments:

![Cluster Plot](link-to-image-if-you-upload-one)

## Requirements

Make sure you have the following Python libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
