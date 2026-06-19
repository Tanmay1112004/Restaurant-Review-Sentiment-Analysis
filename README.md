# 🍴 Restaurant Review Sentiment Analysis — End-to-End NLP Pipeline

<p align="center">
  <b>Transform unstructured customer feedback into actionable business insights</b><br>
  Built using classical NLP + machine learning with strong evaluation and benchmarking
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/NLP-Text%20Processing-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/ML-Model%20Benchmarking-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Focus-Sentiment%20Analysis-red?style=flat-square"/>
</p>

---

## 💡 What This Project Does

This system classifies restaurant reviews into:

* 😊 **Positive Sentiment**
* 😞 **Negative Sentiment**

👉 Converting raw text into **decision-ready insights for businesses**

---

## 🚨 Business Problem

Businesses receive thousands of reviews, but:

* Manual analysis is not scalable
* Key insights are hidden in unstructured text
* Negative feedback often goes unnoticed

👉 Result: Missed opportunities for improvement

---

## 🎯 Solution

A scalable **NLP pipeline** that:

✅ Cleans and preprocesses raw text
✅ Converts text into meaningful numerical features
✅ Benchmarks multiple ML models
✅ Identifies the best-performing classifier
✅ Provides reliable sentiment predictions

---

## ⚡ Key Features

### 🧹 Advanced Text Preprocessing

* Regex-based cleaning
* Stopword removal
* Porter Stemming
* Normalization

---

### 🔤 Dual Vectorization Strategy

* Bag-of-Words (CountVectorizer)
* TF-IDF

👉 Enables comparison of feature representations

---

### 🧠 Multi-Model Benchmarking

Includes 9+ algorithms:

* Logistic Regression
* Naive Bayes
* Support Vector Machine
* KNN
* Decision Tree
* Random Forest
* Gradient Boosting
* XGBoost
* LightGBM

---

### 📊 Robust Evaluation Framework

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC
* Confusion Matrix

---

### 🔁 Cross-Validation

* K-Fold validation
* Reduces overfitting
* Ensures model reliability

---

## 🧬 NLP Pipeline Architecture

```id="nlpflow1"
Raw Reviews
   │
   ▼
Text Cleaning & Normalization
   │
   ▼
Tokenization & Stemming
   │
   ▼
Feature Extraction (BoW / TF-IDF)
   │
   ▼
Model Training (Multiple Algorithms)
   │
   ▼
Evaluation & Benchmarking
   │
   ▼
Best Model Selection
```

---

## 📊 Model Performance Summary

| Model               | Accuracy | Precision | Recall | F1 Score |
| ------------------- | -------- | --------- | ------ | -------- |
| **XGBoost**         | 0.82     | 0.81      | 0.83   | 0.82     |
| Random Forest       | 0.79     | 0.77      | 0.80   | 0.78     |
| Logistic Regression | 0.76     | 0.75      | 0.76   | 0.75     |
| Naive Bayes         | 0.73     | 0.68      | 0.88   | 0.77     |

👉 Insight: Boosting methods outperform traditional models on short-text data

---

## 🧠 Why This Project Stands Out (Recruiter POV)

Most NLP projects:
👉 Train one model and stop

This project:

✅ Benchmarks **multiple algorithms**
✅ Compares **feature engineering strategies**
✅ Uses **robust evaluation metrics**
✅ Demonstrates **end-to-end pipeline thinking**

👉 Translation: *You understand the full ML lifecycle, not just modeling.*

---

## 🛠 Tech Stack

| Layer         | Technology                      |
| ------------- | ------------------------------- |
| Language      | Python                          |
| NLP           | NLTK                            |
| ML            | Scikit-learn, XGBoost, LightGBM |
| Data          | Pandas, NumPy                   |
| Visualization | Matplotlib, Seaborn             |

---

## 🚀 Quick Start

```bash id="runnlp1"
git clone https://github.com/Tanmay1112004/Restaurant-Review-Sentiment-Analysis.git
cd Restaurant-Review-Sentiment-Analysis
pip install -r requirements.txt
```

---

## 📂 Dataset

* File: `Restaurant_Reviews.tsv`
* Size: 1,000 labeled reviews
* Labels:

  * `1` → Positive
  * `0` → Negative

👉 Easily extendable to larger datasets (Yelp, IMDb, Amazon)

---

## 🎯 Real-World Applications

* Customer feedback analysis
* Brand sentiment monitoring
* Product review classification
* Support ticket prioritization

---

## 📈 What This Project Demonstrates

* End-to-end NLP pipeline design
* Feature engineering strategies
* Model benchmarking & evaluation
* Data-driven decision making
* Scalable text classification systems

---

## 🔮 Future Enhancements

* [ ] Deep learning models (LSTM / BERT)
* [ ] Real-time sentiment API (FastAPI)
* [ ] Dashboard integration (Streamlit / Power BI)
* [ ] Multilingual sentiment analysis
* [ ] Aspect-based sentiment analysis

---

## 🤝 Contributing

```bash id="contri_nlp1"
git checkout -b feature/improvement
git commit -m "Improved model performance"
git push origin feature/improvement
```

---

## ⭐ Support

If you found this useful:

* ⭐ Star the repo
* 🍴 Fork it
* 🚀 Extend it

---

## 👨‍💻 Developer Mindset

**From raw text → structured data → actionable insights**

---

## 🔥 Final Thought

Text is messy.

👉 But the right pipeline turns it into **business intelligence.**

---

<p align="center">
  🍴 <b>Understand customers. Improve decisions.</b>
</p>
