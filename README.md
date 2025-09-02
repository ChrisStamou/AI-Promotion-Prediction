# AI-Promotion-Prediction

## Objective
This project showcases how **machine learning** can be applied in **People Analytics** to predict employee promotions in a professional services environment.  
The aim is to replace slow, manual, and subjective promotion analysis with a **data-driven, transparent, and repeatable process** that highlights promotion drivers and supports HR decision-making.

---

## Approach
- **Synthetic Dataset Creation**: Generated data for 5,000 employees, including demographics, tenure, performance ratings, engagement, mentoring, department, and more. The target variable is `promoted_within_12m` (binary).  
- **Exploratory Data Analysis**: Visualized promotion outcomes by gender, department, tenure, performance, engagement, and other key factors to validate dataset realism and uncover initial patterns.  
- **Machine Learning Models**: Trained three models — Logistic Regression, Random Forest, and XGBoost. Evaluated them on Accuracy, Precision, Recall, F1, ROC AUC, and PR AUC.  
- **Interpretability**: Produced feature importance plots and logistic regression coefficients to identify the strongest drivers of promotion (eligibility, performance, engagement, mentorship).  
- **Business Impact**: Compared manual HR processes with AI-assisted analysis. Found that AI reduces promotion analysis from **over a month of HR effort to just hours**, an **85–90% efficiency gain**, while improving consistency and fairness.

---

## Results
- All three models performed well (ROC AUC ≈ 0.77–0.78).  
- **Logistic Regression** provided the best balance between performance and interpretability (ROC AUC = 0.782, Recall = 0.747).  
- Key promotion drivers across models: **eligibility**, **performance rating**, **manager rating**, **engagement**, **utilization**, and **mentorship**.  
- Example outputs include lists of employees most and least likely to be promoted, demonstrating concrete HR use cases.  
- Business analysis shows that using AI saves **hundreds of hours per promotion cycle**, enabling HR to focus on strategic workforce planning.

---

## Repository Contents
- **`AI_Promotion_Prediction.ipynb`** — Jupyter notebook with the full workflow: data generation, EDA, model training, evaluation, and interpretation.  
- **`employees.csv`** — The synthetic dataset of 5,000 employees.  
- **`AI Promotion Prediction.pdf`** — Professional-style report summarizing the methodology, results, and business impact.  
- **`Data Visualization/`** — Plots from exploratory data analysis (promotion distribution, gender, department, tenure, performance, engagement, etc.).  
- **`Feature Importance/`** — Visualizations of feature importance across models (Logistic Regression, Random Forest, XGBoost).  
- **`Model Curves/`** — ROC and Precision–Recall curves for each model, plus combined comparison plots.  
- **`tables_promotion_summary/`** — Numeric summary tables of promotion rates by gender, department, role, mentorship, and performance deciles.  
- **`.gitignore`** — Excludes unnecessary files and system artifacts from version control.  

---

## Key Takeaway
Promotion prediction with AI empowers HR teams to make promotion planning **faster, fairer, and more reliable**.  
It transforms a time-consuming, subjective process into an **evidence-based, transparent workflow** that supports both workforce and financial planning.
