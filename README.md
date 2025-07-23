# 📧 Email Spam Classifier
![Phishing Detection](https://i.pinimg.com/736x/85/a0/2f/85a02f58faaa0bc1b699bec3b209cf43.jpg)

A machine learning project that classifies emails as **Spam** or **Not Spam** using natural language processing (NLP) techniques and various classification algorithms.

---

## 📂 Dataset

The dataset used consists of labeled emails where each email is marked as:
- `spam` — Unwanted messages
- `ham` — Legitimate messages

Most commonly used datasets:
- [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- You can upload your own `.csv` file with two columns: `label` and `message`.
---

## 🔍 Libraries Used
pandas

numpy

matplotlib

seaborn

sklearn

nltk


---

## 🛠️ Features Extracted

- Text cleaning: Lowercasing, removing punctuation, stopwords
- Tokenization
- **Vectorization using `CountVectorizer`** to convert text into numerical format
- Feature matrix for training machine learning models

