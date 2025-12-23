# Bank Term Deposit Predictor 💰

A machine learning project that predicts whether a bank customer will subscribe to a term deposit product. This project tackles the challenge of **imbalanced datasets** using **XGBoost** and class weighting techniques.

## 📌 Project Overview
Direct marketing campaigns are a primary strategy for banks, but they have a low conversion rate. This project utilizes historical campaign data to identify customers who are most likely to subscribe, maximizing marketing efficiency.

## 🛠️ Tech Stack
* **Language:** Python
* **ML Libraries:** XGBoost, Scikit-Learn
* **Analysis:** Pandas, NumPy, Seaborn

## 📊 Methodology
1.  **Data Cleaning:** Handling categorical variables and converting data types.
2.  **EDA:** Analyzed customer demographics (age, job, marital status) vs. subscription rates.
3.  **Handling Imbalance:** Addressed the minority class issue using `scale_pos_weight` in XGBoost.
4.  **Model Training:** Optimized for **Recall** to ensure potential subscribers aren't missed.

## 🚀 How to Run
1.  Install dependencies: `pip install pandas xgboost scikit-learn seaborn`
2.  Run the notebook: `jupyter notebook subscription_prediction.ipynb`