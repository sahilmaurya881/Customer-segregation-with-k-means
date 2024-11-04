# 📊 Customer Segmentation with KMeans Clustering

This project uses **KMeans clustering** to analyze a mall customer dataset, identifying distinct customer segments based on income and spending attributes. Through this segmentation, businesses can gain insights into spending patterns and craft targeted marketing strategies for each segment.

## 📋 Project Overview

This analysis involves the following steps:

1. **Data Loading and Preprocessing**:  
   Clean and prepare the dataset by removing non-essential columns such as `CustomerID`.

2. **Exploratory Data Analysis (EDA)**:  
   - Visualize customer spending habits based on income and spending scores.
   - Analyze customer distributions by age, income, and gender.

3. **KMeans Clustering**:  
   - Apply the elbow method to identify the optimal number of clusters.
   - Cluster customers based on `Annual Income` and `Spending Score`.
   - Visualize clusters with labeled centroids.

## 📂 Key Files

- **`Mall_Customers.csv`**: The dataset containing customer demographic and spending information.
- **`customer_segmentation.ipynb`**: Jupyter notebook containing all code for data analysis, visualization, and clustering.

## 📚 Libraries Used

- **Pandas**: For data manipulation.
- **Matplotlib** & **Seaborn**: For data visualization.
- **Scikit-Learn**: For KMeans clustering and evaluation.
- **NumPy**: For numerical operations.

## 📈 Visualizations

The notebook includes several key visualizations to explore the data and interpret clusters:

- **Pair Plots**: Display demographic factors with gender distribution.
- **Count Plots**: Show the gender distribution in the dataset.
- **Distplots**: Provide insights on age, income, and spending score distributions.
- **Scatter Plots**: Highlight clusters, with centroids marked for each group.

## 🎯 Project Outcomes

This analysis helps segment customers based on spending behavior and income level, enabling businesses to target specific customer groups for personalized marketing and improving strategic decision-making.
