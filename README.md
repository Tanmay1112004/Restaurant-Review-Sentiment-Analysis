# 🍴 Restaurant Review Sentiment Analysis

An end-to-end **Natural Language Processing (NLP)** pipeline designed to classify restaurant reviews into **Positive** or **Negative** sentiments. This project benchmarks various traditional and boosting algorithms to find the most effective classifier for short-form text data.

## 🌟 Key Features

* **Advanced Text Preprocessing**: Robust cleaning pipeline including regex-based noise reduction, stopword removal, and Porter Stemming.
* **Vectorization Techniques**: Support for both **Bag-of-Words (CountVectorizer)** and **TF-IDF** to transform text into numerical features.
* **Comprehensive Model Zoo**: Implementation of 9+ classifiers ranging from Naive Bayes to Gradient Boosting.
* **In-depth Evaluation**: Automated generation of Confusion Matrices, ROC-AUC curves, and classification reports.
* **Cross-Validation**: Built-in K-fold cross-validation to ensure model reliability and prevent overfitting.

---

## 🏗️ The Pipeline

The project follows a standard data science lifecycle:

1. **Data Loading**: Parsing `.tsv` files for tab-separated review data.
2. **Preprocessing**: Lowercasing, removing non-alphabetic characters, and stemming.
3. **Feature Engineering**: Transforming tokens into feature vectors.
4. **Training**: Fitting multiple models to the training set.
5. **Benchmarking**: Comparing models based on the  and Accuracy.

---

## 🧪 Model Performance Matrix

| Algorithm | Accuracy | Precision | Recall | F1-Score |
| --- | --- | --- | --- | --- |
| **XGBoost** | 0.82 | 0.81 | 0.83 | 0.82 |
| **Random Forest** | 0.79 | 0.77 | 0.80 | 0.78 |
| **Naive Bayes** | 0.73 | 0.68 | 0.88 | 0.77 |
| **Logistic Regression** | 0.76 | 0.75 | 0.76 | 0.75 |

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Tanmay1112004/Restaurant-Review-Sentiment-Analysis.git
cd Restaurant-Review-Sentiment-Analysis

```

### 2. Environment Configuration

It is recommended to use a virtual environment to avoid dependency conflicts.

```bash
# Create environment
conda create -n nlp_env python=3.12 -y

# Activate environment
conda activate nlp_env

```

### 3. Install Dependencies

```bash
pip install -r requirements.txt

```

---

## 📊 Dataset Overview

The project utilizes the `Restaurant_Reviews.tsv` dataset, containing:

* **Review**: Raw text feedback from customers.
* **Liked**: Binary label where `1` = Positive and `0` = Negative.

> **Note:** While currently optimized for restaurant data, the pipeline architecture is compatible with any binary text classification task, such as Yelp, IMDb, or Amazon product reviews.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---
