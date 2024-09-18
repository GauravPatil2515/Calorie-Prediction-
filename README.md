# Calorie Prediction Project

## Overview
This project predicts the number of calories burned during exercise using machine learning techniques. The model is trained using features such as age, height, weight, gender, and workout duration.

## Datasets
1. `calories.csv`: Contains information about the number of calories burned.
2. `exercise.csv`: Contains user information and exercise details.

## Libraries Used
- **NumPy**: For numerical operations
- **Pandas**: For data manipulation
- **Matplotlib**: For visualizations
- **Seaborn**: For heatmap visualization
- **Scikit-learn**: For data splitting, model training, and evaluation
- **XGBoost**: For regression modeling

## Project Workflow
1. Load datasets using `pandas`.
2. Preprocess the data (merge, clean, and encode categorical data).
3. Perform exploratory data analysis (EDA) using correlation matrices and visualizations.
4. Split the data into training and testing sets.
5. Train an XGBoost Regressor model to predict calories burned.
6. Evaluate the model using Mean Absolute Error (MAE).
7. Visualize model performance with scatter plots and residual histograms.

## Results
- **MAE**: The Mean Absolute Error is printed, which helps in understanding the model's accuracy.
- The model's performance is visualized using:
  - A scatter plot showing actual vs. predicted values.
  - A histogram of residuals.

## Installation

To install the necessary dependencies, run:
```bash
pip install -r requirements.txt
