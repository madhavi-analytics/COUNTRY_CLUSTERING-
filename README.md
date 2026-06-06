# COUNTRY_CLUSTERING-

Project Overview

This project focuses on Country Clustering using Machine Learning (Unsupervised Learning). The main goal is to analyze country-level socio-economic and health indicators and group countries based on similarities. This helps an international NGO identify countries that require urgent support and better resource allocation. 

Business Problem

An international NGO has limited funds and resources to support countries worldwide. Since not all countries require the same level of help, the NGO needs a data-driven approach to prioritize countries based on economic, health, and social indicators. 

Objective

Analyze country-level data

Identify patterns among countries

Group countries using clustering techniques

Categorize countries into:

Underdeveloped

Developing

Developed

Support better funding decisions for NGOs 

Dataset Features

The dataset includes important indicators such as:

Child Mortality

Exports

Health Spending

Imports

Income

Inflation

Life Expectancy

Total Fertility


GDP per Capita 

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Project Workflow

1. Data Preprocessing

Loaded dataset using Pandas

Checked missing values and duplicates

Removed non-numeric columns

Selected important features for clustering

Applied feature scaling using StandardScaler for better clustering performance

2. Exploratory Data Analysis (EDA)
   
Data distribution analysis

Outlier detection

Feature relationship analysis

Country comparison using socio-economic indicators 
  
3. Clustering Algorithms Used
   
K-Means Clustering

Groups countries into clusters using distance-based similarity

Fast and efficient for large datasets

Hierarchical Clustering

Creates dendrogram structure

Helps visualize country grouping patterns 
   
Results

The countries were grouped into 3 meaningful clusters:

Cluster 1 – Underdeveloped Countries

Low income

High child mortality

Low life expectancy

Cluster 2 – Developing Countries

Moderate income

Medium health conditions

Cluster 3 – Developed Countries

High income

Low child mortality

High life expectancy 
   
Visualizations Used

PCA Scatter Plot

Dendrogram

Elbow Method Graph

These visualizations helped understand cluster separation clearly. 

Key Insights

Developed countries showed better health and economic indicators

Underdeveloped countries had higher child mortality and lower life expectancy

Strong relationship found between economic condition and health indicators

Clear global inequality observed across countries

Conclusion

This project successfully clustered countries into meaningful development groups using machine learning techniques. The insights can help NGOs prioritize countries and allocate resources effectively. 
