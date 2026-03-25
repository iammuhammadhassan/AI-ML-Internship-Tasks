AI/ML Engineering Internship TasksThis repository contains the completed tasks for my AI/ML Engineering Internship at Developers Hub Corporation. Each task is designed to build a strong foundation in data science, from visualization to advanced machine learning and LLM development.Task 1: Exploring and Visualizing a Simple Dataset1. ObjectiveThe goal of this task was to learn how to load, inspect, and visualize a dataset to understand data trends, distributions, and identify outliers.

DatasetName:
Iris

Dataset Format:
Loaded via the seaborn library (standard CSV format)

Features:
Sepal Length, Sepal Width, Petal Length, and Petal Width 

Handling:
pandas for loading and summary statistics (.info(), .describe()).

Visualization: 
matplotlib and seaborn.

Plot Types: 
Scatter plots, Histograms, and Box plots.

Key Results & Findings
Cluster Analysis:
The Scatter Plot revealed that the Setosa species forms a distinct cluster based on petal measurements, making it easily separable from Versicolor and Virginica.

Distribution: 
Histograms showed a bimodal distribution in petal length, confirming the physical gap between different species

Outliers: 
The Box Plot identified a few outliers in the sepal_width feature, which are data points that fall outside the typical range for this dataset.



Task 2:
Predict Future Stock Prices (Short-Term)

Objective:
Use historical data to predict the next day's closing price.

Dataset:
Yahoo Finance (AAPL) data retrieved via yfinance.

Model Applied: 
Linear Regression.


Task 3: Heart Disease Risk Classification
Objective: Classify whether a patient is at risk of heart disease based on clinical features (Age, Cholesterol, Heart Rate, etc.).

Data Challenges: * Handled over 600 missing values using Median and Mode Imputation.

Converted categorical text (e.g., Chest Pain Type) into numerical data via One-Hot Encoding.

Applied StandardScaler to normalize features of different magnitudes (e.g., Age vs. Cholesterol).

Model: Logistic Regression.

Evaluation Metrics:

Accuracy: 83.15%

Confusion Matrix: Used to analyze False Negatives (critical in medical AI).

ROC/AUC: Evaluated the model's ability to distinguish between healthy and high-risk patients.

Key Results: 
Successfully plotted actual vs. predicted prices, showing the model's ability to track market trends.
