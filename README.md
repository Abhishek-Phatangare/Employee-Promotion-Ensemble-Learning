Employee Promotion Prediction Using Ensemble Learning

Comparative Study of Bagging, Boosting, Voting and Stacking Techniques

Author: Abhishek Phatangare
Project: Employee Promotion Prediction Using Ensemble Learning
Target: promoted

📌 Project Overview

This project predicts whether an employee is likely to be promoted using Ensemble Learning. The same employee-promotion problem and dataset are studied from the beginning with a new focus on combining multiple Machine Learning models.

The project compares:

Baseline Machine Learning

Bagging

Boosting

Voting

Stacking

Research Question

Can Ensemble Learning techniques improve employee promotion prediction compared with individual Machine Learning models?

🎯 Objectives

Understand and clean the employee dataset.

Perform Exploratory Data Analysis (EDA).

Prepare numerical and categorical features.

Build baseline models.

Implement Bagging techniques.

Implement Boosting techniques.

Implement Hard and Soft Voting.

Implement Stacking with a meta-learner.

Compare models using multiple evaluation metrics.

Perform 5-fold cross-validation.

Select the best-performing model.

Predict promotion for a new employee.

🧠 Ensemble Techniques

Baseline

Logistic Regression

Decision Tree

Bagging

Random Forest

Extra Trees

Boosting

AdaBoost

Gradient Boosting

XGBoost

HistGradientBoosting

Voting

Hard Voting

Soft Voting

Stacking

Base learners:

Random Forest

Extra Trees

XGBoost

Meta learner:

Logistic Regression

Employee Dataset
      |
      +----------------+----------------+
      |                |                |
 Random Forest     Extra Trees       XGBoost
      |                |                |
      +----------------+----------------+
                       |
                Meta Learner
             Logistic Regression
                       |
                       v
                Final Prediction

🔄 Project Workflow

Raw Dataset
    ↓
Data Understanding
    ↓
Data Cleaning
    ↓
EDA
    ↓
Feature Preparation
    ↓
Train/Test Split
    ↓
Preprocessing
    ↓
Baseline Models
    ↓
Bagging
    ↓
Boosting
    ↓
Voting
    ↓
Stacking
    ↓
Cross Validation
    ↓
Model Evaluation
    ↓
Best Model
    ↓
New Employee Prediction

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

Joblib

Jupyter Notebook / Google Colab / VS Code

📊 Dataset

The target variable is:

promoted

where:

0 = Not Promoted
1 = Promoted

The dataset contains employee attributes including:

employee_id

age

gender

education_level

marital_status

city_tier

department

employment_type

years_at_company

years_in_current_role

years_since_last_promotion

team_size

performance_score

performance_last_year

performance_two_years_ago

manager_rating

peer_feedback_score

projects_completed

kpi_achievement_percent

innovation_score

leadership_score

problem_solving_score

avg_monthly_hours

overtime_hours

tasks_completed

deadline_adherence_rate

meeting_hours_per_month

remote_work_ratio

training_hours_last_year

certifications_count

skill_assessment_score

cross_department_projects

mentoring_sessions

salary

salary_increase_percent

bonus_last_year

stock_options

attendance_rate

late_days

employee_engagement_score

job_satisfaction_score

internal_mobility_score

promoted

🔍 EDA

The notebook analyzes:

Promotion distribution

Department-wise promotion rate

Performance vs promotion

Manager rating vs promotion

KPI achievement

Training and experience

Certifications

Engagement and satisfaction

Attendance

Correlation between numerical variables

📈 Evaluation Metrics

Models are evaluated using:

Accuracy

Precision

Recall

F1-Score

ROC-AUC

Confusion Matrix

5-fold Cross Validation

Training Time

The notebook generates the actual scores from the dataset. No artificial accuracy values are used.

🤖 Model Comparison

Model

Category

Logistic Regression

Baseline

Decision Tree

Baseline

Random Forest

Bagging

Extra Trees

Bagging

AdaBoost

Boosting

Gradient Boosting

Boosting

XGBoost

Boosting

HistGradientBoosting

Boosting

Hard Voting

Voting

Soft Voting

Voting

Stacking

Stacking

📁 Recommended Project Structure

Employee-Promotion-Ensemble-Learning/
│
├── data/
│   └── raw/
│       └── employee_promotion.csv
│
├── models/
│   └── employee_promotion_ensemble_model.pkl
│
├── outputs/
│   ├── ensemble_model_comparison.csv
│   └── ensemble_cross_validation.csv
│
├── notebooks/
│   └── Employee_Promotion_Ensemble_Learning.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore

🚀 Quick Start

1. Clone

git clone https://github.com/Abhishek-Phatangare/Employee-Promotion-Ensemble-Learning.git
cd Employee-Promotion-Ensemble-Learning

2. Create virtual environment

Windows:

python -m venv venv
venv\Scripts\activate

3. Install libraries

pip install -r requirements.txt

4. Add dataset

Put your CSV here:

data/raw/employee_promotion.csv

5. Open Jupyter

jupyter notebook

Open:

notebooks/Employee_Promotion_Ensemble_Learning.ipynb

Run all cells from top to bottom.

📦 requirements.txt

pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
joblib
jupyter
notebook

📌 Expected Outputs

After execution, the notebook produces:

EDA charts

Model comparison table

Confusion matrices

ROC curves

Cross-validation results

Random Forest feature importance

Best model selection

New employee prediction

Saved model and CSV comparison files

🔮 Future Scope

Hyperparameter tuning with GridSearchCV / RandomizedSearchCV

LightGBM and CatBoost comparison

SHAP explainability

Streamlit application

Flask/FastAPI API

Cloud deployment

Fairness and bias analysis

HR analytics dashboard

⚠️ Limitations

This is an academic Machine Learning project. Promotion predictions should not be used as the sole basis for real HR decisions. Historical data may contain bias, and predictions should be reviewed by humans.

📚 References

https://scikit-learn.org/

https://xgboost.readthedocs.io/

https://pandas.pydata.org/docs/

https://numpy.org/doc/

https://matplotlib.org/stable/

https://seaborn.pydata.org/

👨‍💻 Author

Abhishek Phatangare
M.Sc. Computer Science
GitHub: Abhishek-Phatangare

⭐ If you find this project usef