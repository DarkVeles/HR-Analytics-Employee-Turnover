# Employee Turnover Prediction (HR Analytics)

This project aims to predict employee satisfaction and turnover using machine learning.  
HR analytics helps businesses **reduce financial losses and optimize workforce management**  
by identifying employees at risk of leaving the company.

## 📊 Problem Statement
- **Task 1:** Predict employee **satisfaction level** based on provided company data.  
- **Task 2:** Predict if an employee is **likely to leave** the company.  

## 🔥 Key Features
- Regression model for **satisfaction score prediction** (0 to 1 scale).  
- Classification model for **employee turnover prediction** (will leave / will stay).  
- Feature engineering and exploratory data analysis.  
- Business insights for HR teams.  

## 📌 Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning**: Scikit-Learn, LightGBM  
- **Data Processing**: Feature Engineering, Standardization  

## 📂 Dataset
The dataset is publicly available and can be accessed using the following links:

- **Training Data:** [train_job_satisfaction_rate.csv](https://code.s3.yandex.net/datasets/train_job_satisfaction_rate.csv)  
- **Test Features:** [test_features.csv](https://code.s3.yandex.net/datasets/test_features.csv)  
- **Test Target:** [test_target_job_satisfaction_rate.csv](https://code.s3.yandex.net/datasets/test_target_job_satisfaction_rate.csv)  

The script will automatically download these files if they are not found locally.


## 🚀 How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/DarkVeles/HR-Analytics-Employee-Turnover.git
   cd HR-Analytics-Employee-Turnover
