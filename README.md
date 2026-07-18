# Amazon Review Sentiment Analysis using Machine Learning

## Overview

This project performs sentiment analysis on Amazon product reviews using Machine Learning and Natural Language Processing (NLP). The system classifies customer reviews as either **Positive** or **Negative** by preprocessing text, extracting features using TF-IDF, and training machine learning models.

The project compares the performance of **Logistic Regression** and **Naive Bayes** to identify the better algorithm for sentiment classification.

---

## Features

- Text preprocessing and cleaning
- Stopword removal
- TF-IDF Vectorization
- Binary Sentiment Classification
- Model comparison
- Confusion Matrix
- Classification Report
- Custom review prediction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Machine Learning Workflow

```
Amazon Reviews Dataset
          │
          ▼
Data Preprocessing
(Remove Special Characters, Lowercase,
Stopword Removal, Text Cleaning)
          │
          ▼
TF-IDF Vectorization
          │
          ▼
Train-Test Split
          │
          ▼
Model Training
(Logistic Regression & Naive Bayes)
          │
          ▼
Model Evaluation
          │
          ▼
Sentiment Prediction
```

---

## Dataset

The dataset consists of Amazon product reviews with binary sentiment labels.

| Review | Sentiment |
|---------|-----------|
| Amazing product! Highly recommended. | Positive |
| Very poor quality. Waste of money. | Negative |

---

## Algorithms Used

### Logistic Regression
- Binary classification algorithm
- High accuracy
- Easy to interpret
- Best performing model

### Naive Bayes
- Probabilistic classifier
- Fast training
- Good baseline for NLP tasks

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Project Structure

```
Amazon-Review-Sentiment-Analysis/
│
├── dataset/
├── notebook.ipynb
├── train_model.py
├── predict.py
├── requirements.txt
├── README.md
└── screenshots/
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Amazon-Review-Sentiment-Analysis.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the project

```bash
python predict.py
```

---

## Sample Prediction

Input Review

```
The product quality is excellent and delivery was very fast.
```

Prediction

```
Positive
```

Input Review

```
Worst purchase ever. Completely disappointed.
```

Prediction

```
Negative
```

---

## Future Improvements

- Implement LSTM for better sequential learning
- Use BERT for transformer-based sentiment analysis
- Deploy using Streamlit
- Support multi-class sentiment classification

---

## Contributors

- Ekta Bhardwaj
- Sayra Sood
- Vibha Dubey
- Anjali Kalra
- Vedans Rawat

Department of Computer Science & Engineering

UPES Dehradun

---

## License

This project is developed for educational purposes.
