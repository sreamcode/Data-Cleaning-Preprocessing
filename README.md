Data Preprocessing Pipeline
This repository contains a simple step-by-step data preprocessing workflow for preparing datasets for analysis and modeling.
Steps
Import Data
Load the dataset using pandas.
Explore with .info() and .isnull().sum().
Handle Missing Values
Fill missing numerical data with mean/median.
Fill categorical data with mode or use SimpleImputer.
Encode Categorical Variables
Use Label Encoding or One-Hot Encoding.
Normalize/Standardize
Use StandardScaler or MinMaxScaler to scale features.
Visualize and Remove Outliers
Plot boxplots.
Remove outliers using the IQR method.
Requirements
Python 3.x
Jupyter Notebook
pandas, numpy, matplotlib, seaborn, scikit-learn

