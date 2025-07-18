# 💳 Credit Scoring Model

This project is a machine learning solution to predict credit risk using the German Credit dataset. It explores different classification algorithms to determine whether a loan applicant is likely to be a good or bad credit risk.

## 📁 Project Structure

CodeAlpha_Credit-Scoring-Model/
├── notebooks/
│ └── credit_scoring_model.ipynb # Main notebook with preprocessing, modeling, evaluation
├── data/
│ ├── german.data # Raw dataset
│ └── german.doc # Dataset documentation
├── README.md
└── .gitignore


## 📊 Dataset

- **Source**: UCI Machine Learning Repository
- **Description**: Contains 1000 records with 20 features describing credit history, employment, personal status, and more.
- **Target**: Credit Risk (`Good` or `Bad`)

## 🔧 Tools Used

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- Matplotlib / Seaborn

## ✅ What’s Included

- Data preprocessing and feature engineering
- Logistic Regression baseline
- Alternative models: RandomForest, SVM
- ROC Curve and Accuracy Evaluation
- Exported predictions and saved model (using `joblib` or `pickle`)

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/Mfoniso1/CodeAlpha_Credit-Scoring-Model.git
Open the notebook:

cd CodeAlpha_Credit-Scoring-Model/notebooks
jupyter notebook credit_scoring_model.ipynb
📈 Sample Results
Logistic Regression Accuracy: ~80%

ROC Curve: Plotted for visual comparison

🙌 Acknowledgments
UCI ML Repository – German Credit Dataset

CodeAlpha Internship Program

Author: Mfoniso Akpatang
📫 LinkedIn • GitHub
