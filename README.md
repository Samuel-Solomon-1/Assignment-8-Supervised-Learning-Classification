# Supervised Learning Classification - Titanic Survival Prediction

This repository contains the implementation and evaluation of supervised classification models applied to the [Titanic dataset](https://www.kaggle.com/c/titanic/data).  
The project is **Assignment 8** of Introduction to Artificial Intelligence, focusing on end-to-end classification including preprocessing, modeling, evaluation, and deployment strategy.

---

## Project Overview

The objective is to predict whether a passenger survived the Titanic disaster using various features such as age, sex, fare, and passenger class.

We perform:
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Classification using Logistic Regression and Random Forest
- Evaluation using multiple metrics
- Model interpretation with visualizations
- Deployment and monitoring recommendations

---

## Technologies Used

- Python 3
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Jupyter Notebook

---

## Models Implemented

| Model               | Description                                     |
|--------------------|-------------------------------------------------|
| Logistic Regression| Linear baseline model for binary classification |
| Random Forest      | Ensemble model using decision tree estimators   |

---

## Evaluation Metrics

Each model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix
- ROC Curve

---

## Key Results

| Metric     | Logistic Regression | Random Forest |
|------------|---------------------|----------------|
| Accuracy   | 0.7742              | 0.7355         |
| Precision  | 0.7049              | 0.6667         |
| Recall     | 0.7167              | 0.6333         |
| F1 Score   | 0.7107              | 0.6496         |
| ROC-AUC    | 0.8514              | 0.8027         |

**Conclusion**: Logistic Regression outperformed Random Forest across all key metrics and was selected as the best model.

---

## Installation & Running

1. Clone the repository:
```bash
git clone https://github.com/your-username/titanic-classification.git
cd titanic-classification
````

2. (Optional) Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open the notebook:

```bash
jupyter notebook Assignment_8_Titanic_Classification.ipynb
```

---

## Deployment Strategy

Though this project focuses on experimentation, a production-ready deployment could involve:

* Saving the model using `joblib` or `pickle`
* Creating a REST API using **Flask** or **FastAPI**
* Hosting the model via platforms like **Heroku**, **Render**, or **AWS**
* Preprocessing real-time input data on the fly
* Logging model predictions and feedback
* Monitoring performance and retraining with tools like **MLflow** or **Prometheus**

---

## Credits

* Dataset Source: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)
* Author: *Samuel Solomon*
* Course: Introduction to Artificial Intelligence - Assignment 8 (2025)

---
