# Heart_Disease_Prediction_Model
End-to-end machine learning project for heart disease prediction using supervised learning techniques.

📌 Project Overview

A machine learning project that predicts the likelihood of heart disease using patient clinical data. This project demonstrates a complete supervised ML pipeline, including data preprocessing, model training, evaluation, and prediction.

🎯 Objective

To build an accurate and interpretable classification model for early heart disease risk prediction using medical attributes.

🛠️ Tech Stack

Language: Python

Libraries: NumPy, Pandas, Scikit-learn

Model: Logistic Regression

Evaluation Metric: Accuracy Score

📂 Dataset

Heart Disease Dataset sourced from Kaggle (derived from the UCI Heart Disease dataset)

Dataset: [Heart Disease Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/rishidamarla/heart-disease-prediction)

The dataset contains clinical features such as:
- Age
- Gender
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Maximum heart rate achieved
- Other heart-related health measurements

The target variable indicates the presence (1) or absence (0) of heart disease.

🔄 Methodology

Data loading and preprocessing

Exploratory Data Analysis (EDA)

Feature scaling and train-test split

Model training using supervised ML algorithms

Model evaluation using accuracy and confusion matrix

📊 Results

Achieved reliable classification performance on test data

Logistic Regression and Random Forest models showed strong predictive capability

Identified key contributing features such as age, chest pain type, and maximum heart rate

▶️ How to Run

git clone <repository-url>
cd heart-disease-prediction
pip install -r requirements.txt
python main.py




📺 Reference

1.A Comprehensive Machine Learning Framework for Heart Disease Prediction: Performance Evaluation and Future Perspectives
Ali Azimi Lamir et al. — Proposes an ML framework using Logistic Regression, KNN, and Random Forest, with detailed performance evaluation and tuning approaches.

3.Heart Disease Prediction Using Machine Learning Techniques
D. Ratna Kumari et al. — Uses KNN and Random Forest on the Kaggle (UCI) dataset to evaluate heart disease classification accuracy.


⚠️ Disclaimer

This project is intended for educational purposes only and is not a substitute for professional medical diagnosis.

📜 License

MIT License
