# Amazon Review Sentiment Analysis using Machine Learning

## 📌 Project Overview

This project performs sentiment analysis on Amazon product reviews using Machine Learning and Natural Language Processing (NLP). The objective is to classify customer reviews as either **Positive** or **Negative** based on the review text. The project compares the performance of two supervised machine learning algorithms: **Logistic Regression** and **Naive Bayes**.

---

## 🎯 Objectives

- Classify Amazon product reviews into Positive and Negative sentiments.
- Clean and preprocess textual data.
- Convert text into numerical features using TF-IDF Vectorization.
- Train and compare multiple machine learning models.
- Evaluate model performance using standard metrics.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn

---

## 📂 Dataset

The project uses an Amazon Product Reviews dataset containing customer review text and corresponding sentiment labels.

Example:

| Review | Sentiment |
|---------|-----------|
| Amazing product! Highly recommended. | Positive |
| Very poor quality. Waste of money. | Negative |

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Remove special characters
- Convert text to lowercase
- Remove stopwords
- Clean and normalize text

### 2. Feature Extraction
- TF-IDF (Term Frequency–Inverse Document Frequency)

### 3. Machine Learning Models
- Logistic Regression
- Naive Bayes

### 4. Model Evaluation
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🔄 Project Workflow

Dataset

↓

Data Preprocessing

↓

TF-IDF Vectorization

↓

Train-Test Split

↓

Model Training

↓

Model Evaluation

↓

Sentiment Prediction

---

## 📊 Results

The comparison of both machine learning models shows that **Logistic Regression** achieved better classification performance than **Naive Bayes** on the Amazon Reviews dataset.

---

## 📸 Project Outputs

The project includes:

- Dataset Preview
- Confusion Matrix
- Classification Report
- Accuracy Comparison
- Custom Review Prediction

---

## 🚀 Future Improvements

- Implement Deep Learning models such as LSTM.
- Use BERT for transformer-based sentiment analysis.
- Deploy the project using Streamlit or Flask.
- Improve prediction accuracy through hyperparameter tuning.

---



## 📄 License

This project is developed for educational and learning purposes.
