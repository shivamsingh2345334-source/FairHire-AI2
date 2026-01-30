# FairHire AI 🚀  
### Explainable Salary Bias Detection in Indian Job Market

## Problem
Compensation decisions often appear objective but may hide structural bias based on job role and location.  
This project analyzes real Indian job salary data to uncover such patterns using data analytics and explainable machine learning.

## Dataset
- 22,000+ Indian job salary records
- Features include:
  - Job Role
  - Company
  - Location
  - Employment Type
  - Company Rating
  - Salary

## Approach
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Salary Prediction using Random Forest Regression  
4. Feature Importance Analysis to identify bias drivers  
5. Role-location based salary comparison

## Key Findings
- Job role and location are the strongest salary drivers  
- Company rating has limited influence on compensation  
- Identical roles receive significantly different median salaries across cities  
- Indicates structural, location-based pay bias

## Model Performance
- R² Score ≈ 0.06  
- MAE ≈ ₹4 Lakh  

> Lower predictive accuracy is expected due to missing real-world variables like experience, skills, and negotiation factors.  
> The goal of the model is insight discovery, not perfect prediction.

## Conclusion
While salary prediction is inherently noisy, explainable ML reveals clear structural compensation patterns.  
These insights can help organizations design fairer, more transparent pay frameworks.

## Tech Stack
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- GitHub Actions (CI)

---
⭐ If this project helped you understand real-world salary dynamics, feel free to star the repo.

