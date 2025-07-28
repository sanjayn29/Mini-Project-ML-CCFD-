# 💳 Leveraging Machine Learning for Credit Card Fraud Defense

This project aims to build a machine learning-based framework to accurately detect fraudulent credit card transactions using advanced techniques such as SMOTE and AdaBoost, improving upon existing models.

---

## 📌 Problem Statement

Credit card fraud is a critical financial issue globally. This project focuses on creating a machine learning model to classify credit card transactions as **fraudulent** or **legitimate** by analyzing features such as transaction amount, type, time, and more.

---

## 🎯 Objective

- Develop and evaluate a framework for credit card fraud detection.
- Address **class imbalance** in datasets using **SMOTE**.
- Enhance classification performance using **AdaBoost** on multiple machine learning models.
- Compare traditional algorithms with improved ensemble models.

---

## 📚 Literature Review

| Authors | Title | Journal | Year |
|--------|-------|---------|------|
| Abdul Rehman Khalid et al. | Enhancing Credit Card Fraud Detection: An Ensemble Machine Learning Approach | MDPI | 2024 |
| K. A. Bakar et al. | Credit Card Fraud Detector Based on Machine Learning Techniques | JCSTS | 2023 |
| Seyedeh Khadijeh et al. | Fraud Detection in Banking Data by ML Techniques | IEEE Access | 2022 |
| Haritha Nair et al. | An Intelligent Approach to CCFD Using an Optimized Light Gradient Boosting Machine | IEEE Access | 2022 |
| Zhi-Hua Zhou et al. | Performance Evaluation of ML Methods for CCFD Using SMOTE and AdaBoost | IEEE Access | 2021 |

---

## 📂 Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains transactions made by European credit card holders in September 2013.

---

## 🔄 Proposed Work / Workflow

- Apply preprocessing and SMOTE for class balancing.
- Train various ML models: Logistic Regression, Random Forest, Decision Trees, Extra Trees, XGBoost.
- Use **AdaBoost** to improve classification performance.
- Evaluate using metrics like accuracy, correlation matrix, and performance scores.

---

## ✅ Advantages

- ✅ **Higher Accuracy**: Boosting techniques increase detection rates.
- ✅ **Imbalance Handling**: SMOTE improves performance on minority class.
- ✅ **Model Flexibility**: Uses various models including XGBoost and Extra Trees.
- ✅ **Interpretability**: Decision Trees make reasoning transparent.
- ✅ **Scalability**: Can process large-scale transaction data.

---

## 🧪 Models Implemented

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Extra Trees Classifier
- XGBoost
- AdaBoost (for performance boosting)

---

## 📊 Comparative Analysis

| Model | Existing Accuracy (%) | Proposed Accuracy (%) |
|-------|------------------------|------------------------|
| Random Forest | 94.99 | 99.98 |
| Logistic Regression | 92.16 | 93.90 |
| K-Nearest Neighbors | 93.22 | -- |
| SVM | 99.95 | -- |
| XGBoost | -- | 99.97 |
| Extra Trees | -- | 99.98 |
| Decision Tree | -- | 99.80 |

---

## 📈 Performance Metrics

- Correlation Matrix
- Accuracy Scores
- ROC-AUC (if implemented)
- Confusion Matrix
- Precision/Recall/F1-Score

---

## 🛠️ Tools & Technologies

- Python
- Scikit-learn
- XGBoost
- imbalanced-learn (for SMOTE)
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook / VSCode

---

## 📚 References

1. Zhi-Hua Zhou et al. (2021) - IEEE Access.
2. Seyedeh Khadijeh et al. (2022) - IEEE Access.
3. Abdul Rehman Khalid et al. (2024) - MDPI.
4. Haritha Nair et al. (2022) - IEEE Access.
5. K. A. Bakar et al. (2023) - JCSTS.

---

> “Machine learning is not just a buzzword—it’s a defense mechanism in the fight against financial fraud.”
