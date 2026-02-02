# nyc_taxi_tip_prediction
Machine Learning project to predict NYC taxi tip amount

Project Overview

This project focuses on predicting taxi tip amounts using historical NYC Yellow Taxi trip data. By analyzing trip details such as distance, fare, duration, and payment type, a machine learning regression model is built to estimate tipping behavior.

Problem Statement

To predict the tip amount for a taxi trip based on trip and payment-related features using machine learning techniques.


Tech Stack:
Programming Language: Python
Libraries:
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn

Dataset
NYC Yellow Taxi Trip Data

Key features include:
Trip distance
Fare amount
Passenger count
Pickup & drop-off timestamps
Payment type
Total amount

Data Preprocessing & Feature Engineering
Converted pickup and drop-off timestamps to datetime format.
Created a new feature trip duration (in minutes).
Removed records with missing or invalid values.
Converted categorical variables into suitable formats.
Applied One-Hot Encoding using ColumnTransformer.


Exploratory Data Analysis (EDA)
Analyzed the distribution of tip amounts.
Studied the relationship between fare amount, trip distance, and tips.
Visualized correlations using a heatmap.
Used histograms, scatter plots, and box plots for insights.


Model Building
Implemented Linear Regression using Scikit-learn.
Used a Pipeline to combine preprocessing and modeling steps.
Split data into training (80%) and testing (20%) sets.

Model Evaluation
The model performance was evaluated using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score

Results & Conclusion

The model successfully identifies key factors influencing taxi tips, such as fare amount and trip duration. This project demonstrates practical skills in data preprocessing, EDA, and machine learning regression modeling.


Future Improvements
Perform feature importance analysis
Hyperparameter tuning
Deploy the model using Flask or FastAPI



