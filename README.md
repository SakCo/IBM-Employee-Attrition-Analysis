# IBM Employee Attrition Analysis 📊

# Overview
This project analyzes the IBM HR Analytics Employee Attrition & Performance dataset to identify factors driving employee attrition. The dataset, a fictional creation by IBM data scientists, contains 1,470 employee records with 35 features, including age, job role, monthly income, and job satisfaction. By applying data science techniques, this analysis provides actionable insights to help HR professionals reduce turnover and improve retention strategies.

# Objective///
The goal is to predict employee attrition (the rate at which employees leave an organization) and uncover correlations between features such as distance from home, job role, and income with attrition. These insights enable organizations to proactively address turnover risks and optimize workforce management.
Methodology

Data Preprocessing: Cleaned the dataset by handling missing values, encoding categorical variables, and addressing class imbalance using SMOTE (Synthetic Minority Oversampling Technique).
Exploratory Data Analysis (EDA): Employed Pandas, Matplotlib, and Seaborn to visualize feature distributions and correlations, identifying key drivers of attrition.
Feature Engineering: Created new features and applied feature selection techniques, such as Recursive Feature Elimination, to enhance model performance.
Modeling: Implemented machine learning models, including Logistic Regression, Decision Trees, and Random Forest, with hyperparameter tuning via GridSearchCV.
Evaluation: Measured model performance using precision, recall, F1-score, and AUC-ROC to ensure robust and reliable predictions.

# Key Findings

Overtime Impact: Employees working overtime face a higher likelihood of leaving, likely due to increased workplace stress or work-life imbalance.
Commute Distance: Longer distances from home to work correlate with higher attrition rates, possibly due to commuting fatigue.
Job Satisfaction and Income: Higher job satisfaction and monthly income are strongly associated with employee retention, indicating the importance of rewarding roles and positive work environments.
Tenure and Seniority: Employees with longer tenure or higher job levels (e.g., senior roles) are less likely to leave, reflecting the value of career stability and advancement opportunities.

# Repository Structure
IBM-Employee-Attrition-Analysis/
├── data/                   # IBM HR Analytics dataset
├── notebooks/              # Jupyter notebooks for analysis
│   ├── eda.ipynb           # Exploratory data analysis
│   ├── preprocessing.ipynb # Data cleaning and preprocessing
│   ├── modeling.ipynb      # Model training and evaluation
├── scripts/                # Python scripts for automation
│   ├── preprocess.py       # Data preprocessing pipeline
│   ├── train_model.py      # Model training and tuning
├── visualizations/         # Plots and charts from EDA
└── README.md               # Project overview

# Results
The Random Forest model achieved ~87% accuracy after SMOTE and GridSearchCV optimization. Visualizations highlight overtime, commute distance, job satisfaction, and income as key attrition drivers, guiding HR strategies for retention. 🚀

# Acknowledgments

Dataset provided by Kaggle.
Built with open-source libraries: Pandas, Scikit-learn, Matplotlib, and Seaborn.

