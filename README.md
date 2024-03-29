﻿# My-First-ML-project
 
# My First Machine Learning Project

This Python notebook serves as an introduction to a basic machine learning project using a dataset of chemical compounds and their solubility. The project covers data loading, preparation, model building, and performance evaluation.

# Dependencies
Ensure you have the necessary dependencies installed before running the notebook:

* Pandas: pip install pandas
* Scikit-learn: pip install scikit-learn
* Matplotlib: pip install matplotlib
* NumPy: pip install numpy
  
# How to Use
1. Clone the repository to your local machine:

* git clone https://github.com/your-username/my-first-ml-project.git
  
2. Navigate to the project directory:

* cd my-first-ml-project
  
3. Open and run the notebook using Jupyter or any other compatible environment.

# Project Overview
# Data Loading
The project starts by loading a dataset of chemical compounds and their solubility. The dataset is retrieved from a CSV file available on GitHub.

# Data Preparation
The dataset is split into features (X) and the target variable (Y). Further, the data is split into training and testing sets using Scikit-learn's train_test_split.

# Model Building
Two machine learning models are implemented: Linear Regression and Random Forest Regression. The models are trained using the training dataset.

# Model Evaluation
The notebook evaluates the performance of the models using metrics such as Mean Squared Error (MSE) and R-squared (R2) on both training and testing datasets.

# Model Comparison
A summary table is created to compare the performance of the Linear Regression and Random Forest models.

# Data Visualization
The notebook concludes with a visualization of prediction results using Matplotlib. A scatter plot is generated to compare experimental logS values with predicted logS values.

# Acknowledgments
The project uses Pandas for data manipulation, Scikit-learn for machine learning models, and Matplotlib for data visualization.
