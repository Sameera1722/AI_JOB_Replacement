📌 AI Job Automation Risk Classification using Machine Learning
🚀 Project Overview

Artificial Intelligence is rapidly transforming industries and reshaping workforce dynamics. This project builds a multi-class classification model to predict job automation risk levels (Low, Medium, High) using workforce transformation indicators such as skill gaps, AI disruption intensity, and wage volatility.

The goal is to analyze how AI adoption and skill mismatch impact job stability using machine learning techniques.

📊 Dataset Description

Total Records: 15,000

Target Variable: Automation Risk Category

0 → Low Risk

1 → Medium Risk

2 → High Risk

🔎 Key Features

- skill_gap_index

- reskilling_urgency_score

- ai_disruption_intensity

- skill_transition_pressure

- ai_adoption_level

- wage_volatility_index

- salary_change_percent

- job_role

- remote_feasibility_score

- skill_demand_growth_percent

The dataset captures economic and workforce indicators related to AI-driven transformation.

🛠️ Technologies Used

- Python

- Pandas

- NumPy

- Scikit-learn

- XGBoost

- Matplotlib / Seaborn

🔬 Methodology

- Data preprocessing and feature encoding

- Train-test split (80-20)

- Baseline model: Random Forest

- Hyperparameter tuning using GridSearchCV

- Model comparison with XGBoost

- Cross-validation

- Multi-class ROC-AUC evaluation

- Feature importance analysis

📈 Model Performance
- Model	Cross-Validation Accuracy
- Random Forest	96.39%
- Tuned Random Forest	96.28%
- XGBoost	⭐ 97.81%
📊 ROC-AUC

- Multi-class ROC analysis showed near-perfect class separability (AUC ≈ 1.00).

This indicates strong discrimination between automation risk levels.

🔍 Key Insights

1.Skill gap index is the strongest predictor of automation risk.

2.High AI disruption intensity significantly increases risk classification.

3.Boosting models (XGBoost) outperform bagging models (Random Forest).

4.The model demonstrates strong generalization with minimal overfitting.

🎯 Conclusion

The XGBoost model achieved 97.8% cross-validation accuracy, demonstrating strong predictive capability in classifying job automation risk.

The project highlights how workforce transformation metrics can be effectively modeled using ensemble learning techniques.

🚀 Future Improvements

- SHAP-based model explainability

- Streamlit deployment

- Real-world labor market dataset validation

- Feature interaction analysis

📂 Project Structure
├── data/
├── notebooks/
├── xgboost_model.pkl
├── app.py (optional deployment)
└── README.md

👤 Author

SHAIK SAMEERA ,
B.Tech Computer Science (3rd Year)
