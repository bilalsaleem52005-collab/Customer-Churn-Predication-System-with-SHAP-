
🚀 AI-Driven Customer Churn Prediction System

An end-to-end Data Science and Machine Learning project that predicts customer churn in the telecom sector and provides explainable insights through an interactive dashboard.

📌 Project Overview

This system uses machine learning models to predict whether a customer is likely to churn and explains the reasons behind the prediction using Explainable AI (SHAP).
It is deployed through a Streamlit dashboard, enabling real-time predictions, analytics, and business insights.

🎯 Objectives
Predict customer churn using ML models
Identify key factors influencing churn
Provide explainability using SHAP
Build an interactive dashboard for visualization
Support data-driven decision-making

🧠 Technologies Used
Python
Pandas, NumPy (Data Processing)
Scikit-learn (ML Models & Evaluation)
XGBoost (Final Model)
SHAP (Explainable AI)
Streamlit (Dashboard)

📊 Dataset
Telco Customer Churn Dataset
~7,000+ customer records
Features include:
Demographics (gender, senior citizen, etc.)
Services (internet, security, streaming)
Billing (monthly charges, total charges)
Target variable: Churn (Yes/No)

🧼 Data Preprocessing
Handled missing values
Converted data types (e.g., TotalCharges → numeric)
Applied One-Hot Encoding for categorical variables
Scaled numerical features using StandardScaler
Addressed class imbalance using scale_pos_weight

🤖 Machine Learning Models
Logistic Regression
Random Forest
XGBoost (Final Model) ⭐
Why XGBoost?
Handles class imbalance effectively
Captures complex patterns
Provides better recall for churn prediction

⚙️ Model Optimization
RandomizedSearchCV for hyperparameter tuning
5-Fold Cross Validation for robustness
Threshold tuning using F1-score instead of default 0.5

🔍 Explainable AI (SHAP)
Feature importance analysis
SHAP summary plots
SHAP dependence plots
Helps explain why a prediction was made

🖥️ Dashboard (Streamlit)

The system includes multiple interactive pages:

📌 Overview Dashboard – KPIs and churn metrics
🔮 Prediction Page – Predict churn for new customers
📊 Analytics Page – Visual insights and trends
🔍 SHAP Page – Explain model decisions
👥 Customer Comparison – Compare high vs low risk customers
💰 Revenue Impact – Estimate financial loss
📄 Reports Page – Export insights
🏗️ System Architecture
User Input → Data Preprocessing → Feature Engineering → Model Training  
→ XGBoost Model → SHAP Explainability → Predictions → Streamlit Dashboard

📈 Outputs
Churn Prediction (Yes/No)
Probability Score
Risk Level (Low / Medium / High)
Feature-based explanation
Business insights

🔥 Key Features
End-to-end ML pipeline
Explainable AI integration
Interactive dashboard
Business-focused insights
Real-time predictions

🚀 How to Run
# Clone repository
git clone https://github.com/your-username/your-repo.git

# Install dependencies
pip install -r requirements.txt

# Run Streamlit app
streamlit run app.py

📌 Results
Achieved strong predictive performance
Improved churn detection (recall) using XGBoost
Provided interpretable insights using SHAP

🧠 Project Type

This is an end-to-end Data Science project combining:

Machine Learning
Explainable AI
Data Visualization
Business Intelligence

👤 Author

Bilal Saleem


📌 Future Work
Use real-time telecom data
Deploy as a web application (Flask/FastAPI)
Integrate database systems
Add deep learning models
