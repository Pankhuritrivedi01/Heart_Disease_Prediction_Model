# Heart Disease Prediction — Logistic Regression

A supervised machine learning project that predicts the presence or absence of heart disease from **13 clinical features** using **Logistic Regression**.

The project focuses on building and evaluating a complete ML pipeline rather than reporting accuracy alone.

---

## Results

| Metric             |           Score |
| ------------------ | --------------: |
| Dataset            | **303 samples** |
| Features           |          **13** |
| Train / Test       |    **242 / 61** |
| Test Accuracy      |      **80.33%** |
| Precision          |      **76.92%** |
| Recall             |      **90.91%** |
| F1 Score           |      **83.33%** |
| ROC-AUC            |      **0.8690** |
| 5-Fold CV Accuracy |      **83.09%** |

---

## Approach

```text
Dataset
   ↓
Data Exploration & Quality Checks
   ↓
Stratified 80/20 Train-Test Split
   ↓
StandardScaler
   ↓
Logistic Regression
   ↓
Classification + Probability Prediction
   ↓
Evaluation & Cross-Validation
```

### Key implementation decisions

* Used **stratified splitting** to preserve class distribution.
* Applied **StandardScaler**, fitting it only on training data to avoid data leakage.
* Used **Logistic Regression** because it is appropriate for binary classification and provides interpretable coefficients.
* Evaluated using **Accuracy, Precision, Recall, F1, ROC-AUC and Confusion Matrix** instead of accuracy alone.
* Used **5-fold cross-validation** to check performance consistency.
* Used `predict_proba()` to obtain model-estimated class probabilities.
* Analyzed Logistic Regression coefficients for basic model interpretability.

---

## Dataset

**Source:** Kaggle — Heart Disease Prediction Dataset
https://www.kaggle.com/datasets/rishidamarla/heart-disease-prediction

**Size:** 303 samples × 14 columns
**Inputs:** 13 features
**Target:** `target` → 0 / 1

Features include age, sex, chest pain type, resting blood pressure, cholesterol, maximum heart rate, exercise-induced angina, ST depression and other clinical attributes.

---

## Tech Stack

**Python · Pandas · NumPy · Matplotlib · Scikit-learn · Jupyter/Google Colab**

---

## Key Takeaway

The model achieved **80.33% test accuracy**, **90.91% recall**, and **0.8690 ROC-AUC**, while maintaining a **3.97 percentage-point gap** between training and testing accuracy.

The project demonstrates practical understanding of **data preprocessing, leakage prevention, classification, model evaluation, cross-validation and interpretability**.

---

## Future Improvements

* Compare Logistic Regression with Random Forest, SVM and XGBoost
* Hyperparameter tuning
* Probability calibration
* External validation on an independent dataset
* Streamlit/FastAPI deployment

---

### Author

**Pankhuri Trivedi**
B.Tech Bioinformatics | Amity University, Noida

Interested in **Machine Learning · AI · Healthcare · Bioinformatics**


