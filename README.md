# CODSOFT.3
📊 Customer Churn Prediction

This project predicts customer churn (whether a customer will leave a subscription-based service) using machine learning models such as Logistic Regression, Random Forest, and Gradient Boosting.

🚀 Project Overview

Business Problem: Churn is costly for subscription-based businesses.

Goal: Predict whether a customer will churn (1) or stay (0) using demographic, subscription, and usage data.

Models Used:

Logistic Regression

Random Forest

Gradient Boosting

The pipeline includes data preprocessing, model training, evaluation, and feature importance analysis.

📂 Project Structure
📦 customer-churn-prediction
├── customer_churn.csv         # Dataset (replace with your data)
├── churn_prediction.py        # Main script
├── README.md                  # Project documentation
└── requirements.txt           # Python dependencies

⚙️ Installation & Setup

Clone this repo:

git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction


Install dependencies:

pip install -r requirements.txt


Add your dataset (CSV) named customer_churn.csv in the project folder.

Make sure it has a churn column (1 = churn, 0 = active).

Example columns:

customer_id, age, gender, income, monthly_spend, tenure, churn

▶️ Usage

Run the training script:

python churn_prediction.py


This will:

Train Logistic Regression, Random Forest, and Gradient Boosting models

Print evaluation metrics (precision, recall, F1, ROC-AUC)

Plot feature importance for Random Forest

📈 Example Output

Classification Report (precision, recall, f1-score)

ROC-AUC Score (higher = better)

Feature Importance Plot

🔮 Next Steps

Try XGBoost or LightGBM for improved performance

Handle class imbalance (if churners are fewer) with SMOTE or class_weight="balanced"

Deploy with Flask/FastAPI for real-time prediction

📜 Requirements

Example requirements.txt:

pandas
numpy
scikit-learn
matplotlib
