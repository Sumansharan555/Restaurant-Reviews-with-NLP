# 🍽️ Restaurant Review Sentiment Analysis using NLP

## 📌 Project Overview
This project focuses on classifying restaurant reviews as **Positive** or **Negative** using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The objective is to convert raw customer feedback into meaningful numerical features and train a classification model to predict sentiment accurately.

The project is implemented in **Python** and developed using **Google Colab**.

---

## 📂 Dataset Description
- File Format: `.tsv`
- Columns:
  - `Review` → Customer review text
  - `Liked` → Sentiment label (1 = Positive, 0 = Negative)
- Dataset Size: 1000 reviews (balanced dataset)

---

## 🔄 NLP Preprocessing Steps
The following preprocessing steps were applied:
- Removal of special characters using Regular Expressions
- Conversion to lowercase
- Tokenization
- Stopword removal using NLTK
- Stemming using **Porter Stemmer**
- Rejoining tokens into cleaned sentences

---

## 🧠 Feature Extraction
- **Bag of Words (BoW)**
- `CountVectorizer`
- Maximum features: **1500**

---

## 🤖 Machine Learning Model
- **Algorithm**: Gaussian Naive Bayes
- Reason for selection:
  - Works well with text-based feature vectors
  - Computationally efficient
  - Suitable for baseline NLP classification problems

---

## 📊 Model Training & Evaluation
- Train-Test Split: 80% Training, 20% Testing
- Evaluation Metrics:
  - Confusion Matrix
  - Accuracy Score

---

## 🛠️ Libraries Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- re (Regular Expressions)

---

## ▶️ How to Run the Project

### Step 1: Install dependencies
```bash
pip install -r requirements.txt
# Restaurant-Reviews-with-NLP
