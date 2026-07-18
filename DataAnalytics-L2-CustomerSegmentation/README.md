# Customer Segmentation Analysis using K-Means Clustering

## Project Overview

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on their purchasing behavior. By grouping customers with similar characteristics, businesses can better understand customer profiles and design personalized marketing strategies.

The project includes Exploratory Data Analysis (EDA), feature scaling, the Elbow Method for selecting the optimal number of clusters, customer segmentation, cluster visualization, and business recommendations.

## Dataset

The project uses the **Mall Customer Segmentation** dataset containing customer demographic and purchasing information.

### Dataset Features

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Understanding

- Loaded the dataset
- Examined dataset shape
- Checked data types
- Identified missing values
- Verified duplicate records

### 2. Exploratory Data Analysis

- Gender Distribution
- Age Distribution
- Annual Income Distribution
- Spending Score Distribution
- Relationship between Annual Income and Spending Score
- Relationship between Age and Spending Score

### 3. Data Preprocessing

- Selected Annual Income and Spending Score as clustering features
- Applied feature scaling using StandardScaler

### 4. Machine Learning

- Determined the optimal number of clusters using the Elbow Method
- Applied K-Means Clustering
- Assigned cluster labels to customers

### 5. Cluster Analysis

- Analyzed average income and spending score for each cluster
- Calculated the number of customers in each cluster
- Interpreted customer segments

## Customer Segments Identified

The K-Means algorithm identified five customer groups:

- Average Income – Average Spending
- High Income – High Spending
- Low Income – High Spending
- High Income – Low Spending
- Low Income – Low Spending

## Key Insights

- Successfully segmented customers into five distinct groups based on annual income and spending behavior.
- High Income – High Spending customers represent the most valuable customer segment.
- High Income – Low Spending customers have significant purchasing potential and can be targeted through personalized marketing campaigns.
- Low Income – High Spending customers demonstrate strong purchasing behavior and can be retained through loyalty programs.
- Average Income – Average Spending customers contribute consistently to business revenue.
- Customer segmentation enables businesses to understand customer behavior and develop targeted marketing strategies.

## Business Recommendations

- Provide exclusive rewards and premium services to High Income – High Spending customers.
- Encourage High Income – Low Spending customers through personalized promotions and product recommendations.
- Retain Low Income – High Spending customers using loyalty programs and affordable promotional offers.
- Engage Low Income – Low Spending customers through value-based promotions.
- Regularly perform customer segmentation to adapt marketing strategies based on changing customer behavior.

## Conclusion

This project demonstrates how unsupervised machine learning can be applied to identify meaningful customer segments. Using K-Means Clustering, customers were grouped based on purchasing behavior, enabling businesses to improve marketing effectiveness, customer engagement, and decision-making through data-driven insights.

## Repository Structure

```text
DataAnalytics-L2-CustomerSegmentation/
│
├── dataset.csv
├── customer_segmentation.ipynb
└── README.md
```