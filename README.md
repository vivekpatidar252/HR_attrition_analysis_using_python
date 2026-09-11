# HR Employee Attrition Analysis

End-to-end data analysis project on the IBM HR Analytics Employee Attrition dataset — from EDA and statistical hypothesis testing to feature engineering and predictive modeling.

## 📊 Dataset
- **Source:** IBM HR Analytics Employee Attrition dataset (Kaggle)
- **Size:** 1,470 employees, 35 features
- **Overall Attrition Rate:** 16.1%

## 🔍 Key Insights
- **Overtime** is the strongest driver of attrition — employees working overtime leave at **30.5%** vs **10.4%** for those who don't (p = 8.15e-21).
- **Tenure**: employees in their first **0-2 years** show **28.9%** attrition, nearly 2x the overall rate.
- **Job Level & Income**: entry-level employees (Level 1) have **26.3%** attrition vs **4.7%** at Level 4.
- **Environment Satisfaction**: lowest-satisfaction employees show **25.4%** attrition vs 16% average.
- **Department**: Sales (20.6%) and HR (19%) show higher attrition than R&D (13.8%).
- A combined "Overall Satisfaction Score" shows a clear inverse trend with attrition, from 37.7% down to 8.5%.
- All findings statistically validated using Chi-square hypothesis testing (p < 0.05).

## 🤖 Model
Logistic Regression (class-balanced) to predict attrition:
- Accuracy: 75.2%
- Recall (Attrition = Yes): 62%

## 🛠️ Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn

## 📁 Files
- `HR Attrition Analysis.ipynb` — full analysis notebook
- `HR_Attrition_Analysis_Report.pdf` — summary report with insights & recommendations
- `WA_Fn-UseC_-HR-Employee-Attrition.csv` — dataset
