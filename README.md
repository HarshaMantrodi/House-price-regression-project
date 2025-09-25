# Task : Linear Regression for House Price Prediction

This repository contains the solution for Task of the AI & ML Internship with Elevate Labs. The project focuses on building a multiple linear regression model to predict house prices based on various features from the provided `Housing.csv` dataset.

## Project Workflow

1.  **Data Preprocessing:**
    * **Categorical Encoding:** Converted binary features (e.g., `mainroad`, `guestroom`) from 'yes'/'no' to a numerical format (1/0).
    * **One-Hot Encoding:** Transformed the multi-level `furnishingstatus` column into numerical dummy variables.

2.  **Feature Scaling:**
    * Applied `StandardScaler` to all numerical features to ensure they are on a comparable scale, which is crucial for improving the performance of the linear regression model.

3.  **Model Training:**
    * The dataset was split into training (80%) and testing (20%) sets.
    * A multiple linear regression model was trained on the preprocessed and scaled training data using the Scikit-learn library.

4.  **Model Evaluation:**
    * The model's performance was evaluated on the unseen test set using the following metrics:
        * Mean Absolute Error (MAE)
        * Mean Squared Error (MSE)
        * R-squared ($R^2$) Score

## Tools and Libraries Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
