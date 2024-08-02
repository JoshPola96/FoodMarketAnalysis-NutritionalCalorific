# Food Market Analysis - Nutritional & Calorific

Curriculum Work/Big_Data_Analytics

## Overview

This project is developed for the Big Data Analytics curriculum requirement. It utilizes the 'World Food Facts' dataset available on Kaggle. The entire analysis and machine learning techniques are implemented in a single Python notebook using PySpark and deployed on Databricks.

## Dataset

The dataset used is 'World Food Facts' from Kaggle, which contains detailed nutritional information about various food products. You can access the dataset [here](https://www.kaggle.com/openfoodfacts/world-food-facts).

## Techniques and Tools

The following techniques and tools are used in this project:

- **Principal Component Analysis (PCA)**: For dimensionality reduction.
- **Linear Regression (LR)**: For predictive modeling.
- **K-Means Clustering**: For clustering analysis.
- **PySpark**: For big data processing and machine learning.
- **Databricks**: For deployment.

## Project Structure

The project is structured as follows:

1. **Data Loading and Cleaning**:
   - Load the dataset using PySpark.
   - Handle missing values and data inconsistencies.
   - Convert columns to appropriate data types.

2. **Data Transformation**:
   - Drop duplicates and fill null values.
   - Normalize and clean data.

3. **Exploratory Data Analysis (EDA)**:
   - Analyze nutritional values and their distributions.
   - Visualize correlations and trends using heatmaps.

4. **Machine Learning**:
   - **PCA**: Apply PCA for dimensionality reduction and analyze principal components.
   - **Linear Regression**: Train a linear regression model and evaluate its performance.
   - **K-Means Clustering**: Perform clustering and analyze the resulting clusters.

5. **Visualization**:
   - Plot predictions and actual values.
   - Visualize clusters in a 3D plot.

## Getting Started

1. **Setup**:
   - Ensure PySpark is installed and set up in your environment.
   - Install necessary Python packages:
     ```bash
     pip install pyspark seaborn plotly imageio folium
     ```

2. **Run the Notebook**:
   - Open the provided Python notebook in Databricks or a compatible environment.
   - Execute the cells sequentially to perform data analysis and machine learning tasks.

## Disclaimer

Any direct adaptation of this file or dataset will result in zero marks as per the curriculum guidelines.

## Contact

For any questions or clarifications, please contact:

- **Joshua Peter**: [josh19peter96@gmail.com](mailto:josh19peter96@gmail.com)
