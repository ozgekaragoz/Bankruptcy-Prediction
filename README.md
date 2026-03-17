📌 Bankruptcy Prediction with Machine Learning

This project focuses on predicting corporate bankruptcy using machine learning models and financial ratio analysis. The goal is to identify financially distressed companies by leveraging historical financial data and advanced classification techniques.

🔍 Project Overview

In this study, multiple bankruptcy datasets (e.g., Polish and Taiwanese datasets) were analyzed and combined to build robust predictive models. The project includes data preprocessing, feature engineering, model training, and performance evaluation.

Key objectives:

Detect companies at risk of bankruptcy

Compare different machine learning models

Optimize classification performance using threshold tuning

📊 Datasets

The project uses multiple real-world financial datasets:

Polish Bankruptcy Dataset (1–5 year prediction horizons)

Taiwan Bankruptcy Dataset

These datasets contain financial ratios such as liquidity, profitability, and leverage indicators.

⚙️ Methodology

The workflow of the project includes:

Data Preprocessing

Handling missing values

Merging datasets

Feature scaling

Feature Engineering

Financial ratio selection

Data cleaning and transformation

Modeling

CatBoost

LightGBM

XGBoost

Random Forest

Evaluation Metrics

ROC-AUC

PR-AUC

Precision, Recall, F1-score

Threshold Optimization

Adjusting decision thresholds (e.g., 0.4 vs 0.5)

Improving recall for bankruptcy class

📈 Results

LightGBM achieved strong performance with high ROC-AUC and balanced precision-recall tradeoff

Threshold tuning significantly improved bankruptcy detection (recall)

Ensemble-based models outperformed traditional approaches

🛠️ Technologies Used

Python

Pandas, NumPy

Scikit-learn

CatBoost, LightGBM, XGBoost

Jupyter Notebook

📁 Project Structure
├── data/                  # Raw and processed datasets
├── notebooks/            # Experiments and analysis
├── src/                  # (Optional) utility scripts
├── README.md
└── requirements.txt
🎯 Key Contributions

Multi-dataset bankruptcy prediction pipeline

Comparative analysis of ML models

Threshold-based performance optimization

End-to-end data science workflow

🚀 Future Work

Deep learning models

Time-series based financial analysis

Deployment as a decision support system
