# 📧 Email Spam Detector

Machine Learning model to classify spam emails based on trigger words, links, and exclamation marks. Built using Logistic Regression in Python.

## 🚀 Features
- **Spam Words:** Counts trigger words often found in spam (e.g., "free", "win", "click").
- **Exclamations:** Tracks the usage of exclamation marks.
- **Links:** Evaluates the number of hyperlinks or URLs in the email.
- Uses Scikit-learn's `LogisticRegression` for classification.
- Includes a confusion matrix and feature weights visualization.

## 🛠️ Technology Stack
- **Language:** Python
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 📈 Model Performance
This model effectively predicts whether an incoming email is `SPAM (1)` or `NOT SPAM/HAM (0)` based on the provided feature inputs and calculates the probability of an email being spam.
