# PRODIGY_ML_01
House Price Prediction Model
This repository contains a linear regression model designed to predict the prices of houses based on their square footage, number of bedrooms, and number of bathrooms. The model is built using Python and leverages popular data science libraries such as Pandas, NumPy, and Scikit-learn.

The features considered for this model are:
Square Footage: The total area of the house in square feet.
Number of Bedrooms: The total number of bedrooms in the house.
Number of Bathrooms: The total number of bathrooms in the house.

The datasetS used for training and testing the model consists of house listings with the following columns:
Price: The selling price of the house.
SquareFootage: The total area of the house in square feet.
Bedrooms: The number of bedrooms in the house.
Bathrooms: The number of bathrooms in the house.

Model Training
The dataset is split into training and testing sets to evaluate the performance of the model. The following steps outline the training process:
Data Splitting: The data is split into training and testing sets.
Feature Scaling: The features are scaled to ensure they are on a similar scale, which helps in improving the performance of the linear regression model.
Model Fitting: The linear regression model is trained on the training data.
Evaluation: The model is evaluated on the testing data to assess its performance using metrics such as Mean Absolute Error (MAE) and R-squared (R²).
Results
The model's performance is evaluated based on the Mean Absolute Error (MAE) and R-squared (R²) metrics. These metrics provide insights into how well the model is able to predict house prices and how much of the variance in house prices is explained by the model.
