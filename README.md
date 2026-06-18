# Students Depression Analysis 
This project explores how academic pressure, financial stress, CGPA, sleep, and other lifestyle factors relate to self-reported depression among ~27,900 Indian university students, with machine learning models built to predict depression risk and identify its strongest predictors.
 
## Tools
 
Python, Pandas, Scikit-Learn, Matplotlib, Seaborn
 
## Project Overview
 
- Cleaned a real-world survey export containing common data quality issues (malformed text fields, invalid categorical entries, placeholder values).
- Performed exploratory data analysis to surface relationships between academic pressure, financial stress, CGPA, sleep duration, and depression.
- Trained and compared four classification models (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting) to predict depression.
- Identified the strongest predictors of depression using feature importance analysis.
  
## Key Findings
 
- **History of suicidal thoughts**, **academic pressure**, and **financial stress** are the three strongest predictors of depression in this sample, together driving most of the model's predictive signal.
- **CGPA shows almost no relationship with depression** (correlation ≈ 0.02). Academic *pressure* matters far more than academic *performance*.
- Students reporting **less sleep** and **more work/study hours** show higher depression rates.
- The best-performing model (Gradient Boosting) achieves **~85% accuracy and ~0.92 ROC-AUC** on held-out test data.
