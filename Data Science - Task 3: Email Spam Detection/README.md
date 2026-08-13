# Email Spam Detection Using Machine Learning

## 📌 Project Overview

**Email Spam Detection** is a Machine Learning project that classifies messages as **Spam** or **Ham (Not Spam)**. The project uses Natural Language Processing (NLP) techniques to convert text messages into numerical features and applies the **Multinomial Naive Bayes** algorithm to make predictions.

## 🎯 Objective

The main objective of this project is to develop a Machine Learning model that can automatically identify unwanted or fraudulent messages and classify them as spam.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📊 Dataset

The project uses a labeled SMS/email dataset containing two main columns:

* **Label:** `ham` or `spam`
* **Message:** Text of the email/message

Example:

| Label | Message                                |
| ----- | -------------------------------------- |
| ham   | Hey, how are you?                      |
| spam  | Congratulations! You won a free prize! |

## 🔄 Methodology

The project follows these steps:

1. Load the dataset.
2. Clean and preprocess the data.
3. Convert `ham` and `spam` labels into numerical values.
4. Split the dataset into training and testing sets.
5. Convert text into numerical features using **TF-IDF Vectorization**.
6. Train a **Multinomial Naive Bayes** classification model.
7. Predict whether new messages are spam or ham.
8. Evaluate the model using accuracy, classification report, and confusion matrix.

## 🤖 Machine Learning Algorithm

**Multinomial Naive Bayes** is used because it works effectively with text classification problems. It learns the relationship between words and message categories and uses this information to classify new messages.

## 📈 Model Evaluation

The model is evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help determine how accurately the model identifies spam and legitimate messages.

## 💻 Installation

Install the required libraries using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## ▶️ How to Run

1. Open the project in **Jupyter Notebook** or **VS Code**.
2. Place the dataset file in the project folder.
3. Run the Python code step by step.
4. Train the Machine Learning model.
5. Enter a new message to check whether it is **SPAM** or **HAM**.

### Example

```text
Input:
Congratulations! You have won a free lottery prize. Claim now!

Output:
SPAM
```

```text
Input:
Hi, please send me today's lecture notes.

Output:
HAM
```

## ✅ Advantages

* Automatically detects unwanted messages.
* Saves time by filtering spam.
* Easy to implement and understand.
* Can provide fast predictions.
* Demonstrates a practical application of Machine Learning and NLP.

## 🔮 Future Scope

The project can be improved by using larger datasets, advanced NLP techniques, multiple Machine Learning algorithms, and a web-based application for real-time spam detection.

## 👩‍💻 Author

**B.Sc. Computer Science Student**

**Project:** Email Spam Detection Using Machine Learning

## 📜 License

This project is developed for **educational and academic purposes**.

