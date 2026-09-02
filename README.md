Disease Prediction System — Week 2: Data Cleaning & Transformation

Week 2 deliverable for the Virtual Data Science Apprentice – Python Specialist Intern program (NSDC YuvaIntern). This week documents the data cleaning and transformation strategy for the UCI Heart Disease dataset.



⚠️ Disclaimer: Educational/portfolio project only — not a medical diagnostic tool.



Objective

Document a Python-based plan for handling missing values, duplicates, outliers, and feature transformation to produce an analysis-ready dataset.


Contents

week2-data-cleaning/
├── Week2_Data_Cleaning_Transformation.docx   # Full cleaning & transformation plan
└── README.md

What's in the Report


Data quality profiling approach (nulls, sentinel placeholder values, duplicates, invalid ranges)

Missing value strategy: median/mode imputation, KNNImputer, row removal thresholds

Duplicate detection and removal (pandas.drop_duplicates)

Outlier detection: IQR method, z-score method, box-plot confirmation

Encoding plan: label encoding (binary fields) and one-hot encoding (nominal fields)

Feature scaling: StandardScaler, applied strictly after the train/test split to avoid leakage

Two proposed engineered features (age-group bucket, cholesterol × blood pressure interaction)

An 8-step repeatable cleaning pipeline

Risk table covering leakage prevention and over-aggressive outlier removal


Tools

pandas, numpy, scikit-learn (KNNImputer, StandardScaler, OneHotEncoder)


Depends On

Week 1 project plan and dataset selection.


Next Step

Week 3 will use the cleaned dataset for exploratory data analysis and visualization.


Author

[Your Name] — Virtual Data Science Apprentice, NSDC YuvaIntern

