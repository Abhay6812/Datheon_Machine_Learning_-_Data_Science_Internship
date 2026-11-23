# Machine Learning Projects 🚀

A collection of hands-on Machine Learning projects developed as part of my learning journey with **Datheon**. These projects focus on understanding the end-to-end ML workflow, including data preprocessing, feature engineering, model training, evaluation, and experimentation with different algorithms.

Rather than focusing solely on model accuracy, the objective is to understand how different algorithms work, how data influences predictions, and how to evaluate models effectively.

---

## 📂 Projects Included

### 1. Iris Multi-Class Classification

**Objective:** Classify Iris flowers into their respective species using flower measurements.

The Iris dataset contains measurements such as sepal length, sepal width, petal length, and petal width. The project explores how different classification algorithms perform on a multiclass classification problem.

**Key Work:**
- Exploratory data analysis
- Feature scaling
- Train-test splitting
- Logistic Regression
- Decision Tree Classifier
- Model comparison
- Confusion matrix and classification report
- Evaluation using Accuracy, Precision, Recall, and F1-score

**Models Implemented:**
- Logistic Regression
- Decision Tree Classifier

**Results:**

| Model | Accuracy | Weighted F1-score |
|---|---:|---:|
| Logistic Regression | 93.33% | 93.33% |
| Decision Tree | 93.33% | 93.33% |

**Key Learning:** Understanding multiclass classification, the importance of feature scaling, model comparison, and evaluating classification performance beyond accuracy.

---

### 2. California Housing Price Prediction

**Objective:** Predict median house values in California using housing-related features.

This project uses the California Housing dataset to investigate how demographic, geographical, and housing-related variables influence median house prices. Different regression techniques are implemented and compared, with a focus on regularization and model performance.

**Key Work:**
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Feature engineering
- Creation of interaction and ratio-based features
- Missing value imputation
- Feature scaling using StandardScaler
- Multicollinearity investigation
- Linear Regression (OLS)
- Ridge Regression (L2 Regularization)
- Lasso Regression (L1 Regularization)
- Hyperparameter tuning using GridSearchCV
- 5-Fold Cross-Validation
- Residual analysis and prediction visualization

**Models Implemented:**
- Ordinary Least Squares (Linear Regression)
- Ridge Regression
- Lasso Regression
- Tuned Ridge Regression
- Tuned Lasso Regression

**Model Evaluation:**

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression (OLS) | 0.4862 | 0.6753 | 0.6519 |
| Ridge (α = 1) | 0.4862 | 0.6754 | 0.6519 |
| Lasso (α = 0.01) | 0.4908 | 0.6823 | 0.6447 |
| Tuned Ridge (α = 10) | 0.4862 | 0.6754 | 0.6519 |
| Tuned Lasso (α = 0.001) | 0.4863 | 0.6757 | 0.6516 |

**Best Performance:**
- **R² Score:** 65.19%
- **RMSE:** 0.6753
- **MAE:** 0.4862

**Key Learning:** Understanding the impact of regularization, feature relationships, multicollinearity, cross-validation, and why tuning more complex models does not necessarily guarantee better performance.

---

## 🛠️ Technologies & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Machine Learning Workflow

Both projects follow a structured Machine Learning workflow:

1. Data collection/loading
2. Exploratory Data Analysis
3. Data preprocessing
4. Feature engineering (where applicable)
5. Train-test split
6. Model training
7. Hyperparameter tuning (where applicable)
8. Model evaluation
9. Result interpretation and visualization

---

## 📁 Repository Structure

```text
Machine-Learning-Projects/
│
├── Task-1-Iris-Classification/
│   ├── Iris_MultiClass_Classification_Benchmark.ipynb
│   └── README.md
│
├── Task-2-California-Housing-Regression/
│   ├── California_Housing_Regression_Benchmark.ipynb
│   └── README.md
│
└── README.md
```

---

## 🎯 Purpose

This repository represents my ongoing journey toward building a strong foundation in Machine Learning through practical implementation.

My focus is on:
- Strengthening ML fundamentals
- Understanding algorithms beyond theory
- Experimenting with different models
- Learning proper evaluation techniques
- Developing problem-solving skills through hands-on projects

More projects and experiments will be added as I continue learning.

---

## 🙌 Acknowledgment

These projects are part of my learning journey with **Datheon**, helping me build practical experience and deepen my understanding of Machine Learning.

---

⭐ If you find these projects interesting, feel free to explore the notebooks.
