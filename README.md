# MLInboxGuard
A machine learning-based web application that classifies SMS messages as Spam or Not Spam. The model is trained using a dataset of labeled SMS messages and utilizes natural language processing (NLP) techniques like TF-IDF vectorization combined with a Multinomial Naive Bayes classifier.

 
🔍 Overview
This project is a machine learning-based SMS classification system built with Python, Scikit-learn, and Streamlit. It aims to distinguish between spam and non-spam (ham) messages using natural language processing (NLP) techniques.

During development, multiple classification algorithms were tested and compared, including:

◉ Multinomial Naive Bayes (Final Model) – Achieved highest accuracy and speed for text classification
◉ Logistic Regression – Performed well but slightly lower recall on spam messages
◉ Support Vector Machine (SVM) – High precision, but computationally heavier
◉ Random Forest – Good accuracy but slower and prone to overfitting on small text data

The models were evaluated based on accuracy, precision, recall, and F1-score, with Multinomial Naive Bayes delivering the best balance of performance and simplicity for text classification. The selected model uses TF-IDF vectorization and is deployed via Streamlit for real-time prediction.


🚀 Features

- Clean and simple UI built with Streamlit
- Real-time SMS classification
- Text preprocessing: lowercasing, punctuation removal, stopword removal
- TF-IDF vectorization of text
- Model training and evaluation in Jupyter Notebook
- Trained model and vectorizer saved with `pickle`

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Streamlit
- Pickle

