# 🌸 Iris Flower Classification Using Machine Learning

## 📌 Project Overview

Iris Flower Classification is a **Machine Learning classification project** that predicts the species of an Iris flower based on its physical measurements. The project uses the famous **Iris dataset**, which contains measurements of sepal length, sepal width, petal length, and petal width. A **K-Nearest Neighbors (KNN)** algorithm is used to train the model and classify flowers into three species: **Iris Setosa, Iris Versicolor, and Iris Virginica**.

## 🎯 Objective

The main objective of this project is to build a machine learning model that can accurately classify Iris flowers into their respective species using flower measurements. The project also demonstrates data preprocessing, model training, prediction, and performance evaluation.

## 📊 Dataset

The Iris dataset contains **150 observations** and **4 features**:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

Target classes:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data handling
* **Matplotlib** – Data visualization
* **Scikit-learn** – Machine Learning
* **Jupyter Notebook** – Development environment

## 🤖 Machine Learning Algorithm

The project uses the **K-Nearest Neighbors (KNN)** classification algorithm. Before training, the features are standardized using `StandardScaler`. The dataset is divided into training and testing sets, and the trained model is used to predict the species of new flowers.

## 🔄 Project Workflow

1. Import required libraries
2. Load the Iris dataset
3. Explore and analyze the dataset
4. Visualize the data
5. Split data into training and testing sets
6. Scale the features
7. Train the KNN model
8. Make predictions
9. Evaluate model performance
10. Predict the species of a new flower

## 📈 Model Evaluation

The model performance is evaluated using:

* **Accuracy Score**
* **Classification Report**
* **Confusion Matrix**

The KNN model generally provides very high accuracy on the Iris dataset, making it suitable for this classification problem.

## 🔮 Sample Prediction

For a new flower with measurements:

`[5.1, 3.5, 1.4, 0.2]`

the model predicts:

**Iris Setosa**

## ✅ Conclusion

The Iris Flower Classification project successfully demonstrates how Machine Learning can be used to classify data into different categories. Using the KNN algorithm and basic preprocessing techniques, the model can accurately identify Iris flower species from their measurements. This project is useful for understanding the basic concepts of **classification, data preprocessing, model training, prediction, and evaluation** in Machine Learning.

