# students_depression_analysis1
## 📌 Project Overview
This project explores the relationships between academic pressure, CGPA, financial stress, and depression levels in students. Using a cleaned dataset of over 27,000 records, I performed Exploratory Data Analysis (EDA) and built machine learning models to identify key risk correlates.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib

## 📊 Key Insights from EDA
- **The CGPA Paradox:** High-achieving students with high CGPAs show heavily overlapping rates of depression compared to lower-scoring peers. This indicates that academic marks alone are not a standalone protector or predictor against mental stress.


## 🤖 Modeling Leaderboard
I benchmarked four models using a stratified 80/20 train-test split to ensure class balance:
- Logistic Regression
- Decision Tree (Max Depth: 6)
- Random Forest
- Gradient Boosting

## ⚠️ Caveat & Scope
All features are self-reported and cross-sectional (collected at a single point in time), so the model is best read as identifying *risk correlates* to flag for follow-up—not as a diagnostic or causal tool.
