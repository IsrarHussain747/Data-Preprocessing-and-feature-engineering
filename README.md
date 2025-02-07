Data Preprocessing for Machine Learning

Overview

This repository contains a Python script for preprocessing a dataset before applying machine learning models. The preprocessing steps include handling missing values, feature scaling, encoding categorical variables, and data visualization.

Steps in Data Preprocessing

1. Handling Missing Values

Imputed missing values in Age using the mean.

Imputed missing values in Salary using the median.

Imputed missing values in Experience using the mode.

2. Feature Scaling

Min-Max Scaling: Normalized Age and Salary between 0 and 1.

Z-score Standardization: Standardized Age and Salary with mean 0 and standard deviation 1.

3. Encoding Categorical Variables

One-Hot Encoding: Applied to Education_Level to create binary columns.

Label Encoding: Applied to City column to convert categories into numeric labels.

4. Data Visualization

Correlation Heatmap: Displayed correlations between numerical variables.

Pair Plots: Visualized relationships among dataset features.

Requirements

To run the preprocessing script, install the following dependencies:

pip install pandas numpy scikit-learn seaborn matplotlib

Usage

Run the script to preprocess the dataset:
python preprocess.py
