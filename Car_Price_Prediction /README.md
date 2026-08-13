# Car Price Prediction Using Machine Learning

## Project Overview

Car Price Prediction is a Machine Learning project that predicts the price of a car based on its features. The project uses a **Random Forest Regression** algorithm to learn the relationship between car specifications and their prices.

## Dataset

The dataset contains **2,500 car records and 10 columns**:

* Car ID
* Brand
* Year
* Engine Size
* Fuel Type
* Transmission
* Mileage
* Condition
* Price
* Model

The **Price** column is used as the target variable.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Machine Learning Algorithm

**Random Forest Regressor** is used for prediction. Categorical features such as Brand, Fuel Type, Transmission, Condition, and Model are converted into numerical features using **One-Hot Encoding (`pd.get_dummies()`)**.

## Project Workflow

1. Load the car price dataset.
2. Explore the dataset and check its shape and information.
3. Check and handle missing values.
4. Visualize car prices and relationships between features.
5. Convert categorical data into numerical data.
6. Remove the unnecessary Car ID column.
7. Separate features (`X`) and target (`Y`).
8. Split the dataset into **80% training and 20% testing** data.
9. Train the Random Forest Regression model.
10. Predict car prices using the test data.
11. Evaluate the model using MAE, MSE, RMSE, and R² Score.
12. Display an **Actual vs Predicted Price** graph.
13. Predict the price of a new car using its specifications.

## Model Evaluation

The following evaluation metrics are used:

* **MAE (Mean Absolute Error):** Measures the average prediction error.
* **MSE (Mean Squared Error):** Measures the squared prediction error.
* **RMSE (Root Mean Squared Error):** Measures the standard prediction error.
* **R² Score:** Shows how well the model explains the variation in car prices.

## Result

The trained Random Forest model can predict car prices based on important features such as brand, year, engine size, fuel type, transmission, mileage, condition, and model. The Actual vs Predicted graph helps visually compare the model's predictions with the actual prices.

## Conclusion

This project demonstrates how Machine Learning can be used for **car price prediction**. Random Forest Regression provides an effective approach for handling different numerical and categorical car features. The project can be further improved by using larger datasets, feature engineering, hyperparameter tuning, and other regression algorithms.

