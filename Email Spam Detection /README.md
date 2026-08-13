# 📧 Email Spam Detection Using Machine Learning

## 📌 Project Overview

Email Spam Detection is a Machine Learning project that identifies whether an email is **Spam** or **Not Spam**. The project uses Natural Language Processing (NLP) to convert email text into numerical features using **TF-IDF Vectorization** and then classifies the emails using the **Multinomial Naive Bayes** algorithm.

## 🎯 Objectives

* To detect spam and non-spam emails automatically.
* To preprocess and analyze email text.
* To convert text into numerical data using TF-IDF.
* To train a Machine Learning classification model.
* To evaluate the model using accuracy, classification report, and confusion matrix.
* To predict whether a new email is Spam or Not Spam.

## 📊 Dataset

The project uses a Kaggle Spam Email Dataset containing two main columns:

* `text` — Email message/content.
* `spam` — Target label, where `0` represents Not Spam and `1` represents Spam.

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TF-IDF Vectorizer
* Multinomial Naive Bayes

## 🔄 Methodology

1. Load the Kaggle dataset.
2. Check and remove missing values.
3. Analyze Spam and Not Spam email distribution.
4. Separate input (`text`) and target (`spam`).
5. Split the dataset into 80% training and 20% testing data.
6. Convert email text into numerical features using TF-IDF.
7. Train a Multinomial Naive Bayes model.
8. Predict Spam/Not Spam emails.
9. Evaluate the model using accuracy, classification report, and confusion matrix.
10. Test the model with new email messages.

## 🤖 Machine Learning Algorithm

**Multinomial Naive Bayes** is a supervised classification algorithm that works particularly well with text-based data. It learns patterns from previously labeled emails and predicts the class of new emails.

## 📈 Model Evaluation

The model is evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Actual vs Predicted Graph

## 📁 Project Structure

```text
Email-Spam-Detection/
│
├── emails.csv
├── email_spam_detection.ipynb
├── spam_email_model.pkl
├── tfidf_vectorizer.pkl
├── requirements.txt
└── README.md
```

## ✅ Conclusion

The Email Spam Detection project demonstrates how Machine Learning and NLP can be used to automatically classify emails. By combining **TF-IDF Vectorization** with **Multinomial Naive Bayes**, the system can identify whether a given email is Spam or Not Spam and can also be used to classify new email messages.

## 👩‍💻 Author

**Gauri**
B.Sc. Computer Science
Mini Project – Machine Learning

## 📜 License

This project is created for educational and academic purposes.

