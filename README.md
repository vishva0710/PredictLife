# PredictLife

A Machine Learning project that predicts a person's estimated age at death based on lifestyle, health, and demographic factors — built using Python, Scikit-learn, and XGBoost.

##  Project Overview

This project uses real-world-style health and lifestyle data to train regression models that predict life expectancy. It includes an interactive terminal-based prediction system where users can input their personal data and receive a predicted death age.

##  Features

- End-to-end ML pipeline: data cleaning → encoding → scaling → training → prediction
- Trained on lifestyle, health, and demographic features
- Two models compared: Random Forest & XGBoost
- Interactive user input system with BMI auto-calculation
- Correlation heatmap for feature analysis


## Dataset

**File:** `Final_Cleaned_Life_Expectancy_Data.csv`

**Key Features Used:**

| Category      | Features                                                                 |
|---------------|--------------------------------------------------------------------------|
| Demographics  | gender, current_age, income, urban_vs_rural                              |
| Lifestyle     | smoking, alcohol, diet_type, sleeping_hours, working_hours, exercise     |
| Health        | bmi, diseases, mental_health_level, job_stress_level                     |
| Family        | parents_avg_death_age                                                    |
| Social        | marital_status                                                           |

**Target Variable:** `age_at_death`


## 🧠 Models Used

| Model                  | Library    | Purpose              |
|------------------------|------------|----------------------|
| Random Forest Regressor| Scikit-learn | Baseline model     |
| XGBoost Regressor      | XGBoost    | Final prediction model |

**Evaluation Metrics:** R² Score, Mean Absolute Error (MAE)


## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Seaborn, Matplotlib

