🏠 Boston House Price Prediction

This beginner-level project was completed as part of the ShadowFox AIML Internship. The goal is to predict Boston housing prices using a Linear Regression model trained on the Boston Housing dataset.

📌 Objective

The aim of this project is to build a regression model that predicts median house prices (MEDV) based on various factors such as:
CRIM – Crime rate
RM – Average number of rooms per dwelling
TAX – Property tax rate
LSTAT – % lower status population
...and more.

💻 Tools & Libraries Used

Python
Pandas, NumPy
Matplotlib, Seaborn
scikit-learn

🧠 Steps Followed

1.Load the Dataset
      Imported CSV data into a Pandas DataFrame.
2.Data Cleaning
      Removed unwanted header rows
      Converted object columns to numeric
      Handled missing values
3.Exploratory Data Analysis (EDA)
      Checked correlations with heatmaps
      Visualized relationships between features and target
4.Model Training
      Split data into train (80%) and test (20%) sets
      Trained a Linear Regression model
5.Model Evaluation
     Calculated Mean Squared Error (MSE) and R² Score
    Plotted Actual vs Predicted prices

📊 Results

Mean Squared Error (MSE): ~22 (varies on run)
R² Score: ~0.7–0.8
Scatter plot shows a clear positive relationship between actual and predicted values.
