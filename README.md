Non-Linear Regression on Tabular Data
Project Overview

This project focuses on implementing and evaluating non-linear regression models using structured numerical data. The goal is to predict a continuous target variable by learning complex patterns between input features and the output.

The project demonstrates a complete machine learning workflow, including data loading, preprocessing, model training, evaluation, and visualization.

What This Project Covers

Loading and handling tabular data using Pandas

Selecting numerical features for modeling

Splitting data into training and testing sets

Training non-linear regression models

Evaluating model performance using standard regression metrics

Visualizing actual vs predicted results

Models Used
Decision Tree Regressor

A tree-based model that splits data based on feature values. It captures non-linear relationships but may overfit if not properly controlled.

Random Forest Regressor

An ensemble model that combines multiple decision trees and averages their predictions. It reduces overfitting and improves generalization compared to a single decision tree.

Evaluation Metrics

The models are evaluated using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

These metrics help measure prediction accuracy and how well the model generalizes to unseen data.

Visualization

A scatter plot of actual vs predicted values is generated to visually assess model performance. If predictions closely follow the diagonal line, the model is performing well.
