**E-Commerce Customer Segmentation & Categorization**

**Project Overview**

This project analyzes 400K+ e-commerce transactions from a one-year purchasing dataset to uncover customer purchasing behavior, product patterns, and high-value customer segments.
The solution combines data analytics, NLP, clustering, and supervised machine learning to support customer segmentation and business decision-making.

 **Objectives**

Segment customers based on purchasing behavior and basket value

Identify high-value and low-value customer groups

Categorize products using NLP-based keyword extraction

Build predictive models to classify customers into meaningful segments

 **Dataset**

Source: Kaggle – E-Commerce Dataset

Records: 400,000+ transactions

Features: Invoice, Product, Quantity, Price, Customer ID, Country

Link: https://www.kaggle.com/datasets/carrie1/ecommerce-data

**Tech Stack**

Programming: Python

Data Processing: pandas, numpy

Visualization: matplotlib, seaborn, plotly

Machine Learning: scikit-learn

NLP: nltk

Environment: Jupyter Notebook

**Project Workflow**
1. Data Preparation

Removed missing values and duplicate records

Converted date fields and optimized data types

Engineered new features such as Total Basket Price

2. Exploratory Data Analysis (EDA)

Country-level analysis of customers and orders

Identified canceled transactions (~16%)

Analyzed customer purchase frequency and quantity distributions

3. Product & Customer Segmentation

Extracted keywords from product descriptions using NLP

Clustered products using K-Means with silhouette score validation

Segmented customers based on purchase behavior and spend

4. Customer Classification

Trained supervised ML models to classify customer segments:

Logistic Regression

Support Vector Machine (SVM)

k-Nearest Neighbors (KNN)

Decision Tree

Random Forest

**Key Results**

Successfully segmented distinct customer groups, including high-value buyers

Identified top customers contributing disproportionately to total revenue

Improved customer classification performance by ~20% through feature engineering

Enabled data-driven insights for marketing and customer retention strategies

**Key Takeaways**

Customer behavior can be effectively modeled using combined ML + NLP approaches

Feature engineering (basket price, cancellations, frequency) significantly boosts model performance

Clustering + classification provides both exploratory insights and predictive capability
