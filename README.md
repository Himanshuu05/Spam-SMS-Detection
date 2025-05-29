# 📧 Spam SMS Detection using Machine Learning

This project is a simple yet effective spam mail (SMS/email) detection system using natural language processing (NLP) and machine learning techniques. The model is trained to classify messages as **spam** or **ham** (not spam).

---

## 🔍 Overview

The goal of this project is to apply text preprocessing and supervised learning techniques to detect and filter spam messages. It uses the popular [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection) and is built entirely in Python.

---

## 💡 Features

- Text preprocessing (lowercasing, punctuation removal, stemming, stopword removal)
- Bag-of-Words model using `CountVectorizer`
- Spam classification using `Multinomial Naive Bayes`
- Model evaluation with accuracy, confusion matrix, and classification report
- Easily extendable to email datasets or deployment in web apps

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **NLTK** (optional, replaced here with custom stopwords)
- **Matplotlib/Seaborn** (optional, for data visualization)

---

## 📁 Dataset

- Source: [UCI SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)
- Format: `.csv` with two main columns:
  - `v1`: label (`ham` or `spam`)
  - `v2`: message text

---

## ⚙️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/spam-mail-detection.git
   cd spam-mail-detection
## Results
Accuracy: ~97.76%

Precision (Spam): 0.91

Recall (Spam): 0.92

F1-Score (Spam): 0.92

