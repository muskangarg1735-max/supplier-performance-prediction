# Supplier Performance Prediction | Random Forest - 91.88% Accuracy

> Predicting supplier performance (PerformInd) to help businesses identify high-risk suppliers early.

## 📊 Dataset
- Source: SupplierPerformance.xlsx (~986 records)
- Target: PerformInd (0 = Good Performance, 1 = Poor/Risk)
- Features (20+): FinancialHealthScore, SupplierAssociationYears, SupplierIncome, Visit History (Last3M/6M/12M/36M), SelfAppraisal Q1-Q6, Feedback, SupplierCategory

## 🛠️ Tech Stack
Python, Pandas, NumPy, Scikit-Learn, Matplotlib

## 🔄 Workflow
1. Data Cleaning & Encoding categorical variables
2. EDA - Analyzed Financial Health, Category, Visit frequency
3. Train-Test Split (80-20, random_state=42)
4. Model Training - RandomForestClassifier
5. Evaluation - Accuracy, Confusion Matrix, Classification Report

## 🏆 Results
- **Model:** RandomForestClassifier(random_state=42)
- **Accuracy:** 91.87%
- **Confusion Matrix:** [[155, 6], [10, 26]]
- **F1-Score:** 0.95 (Class 0), 0.76 (Class 1) | Weighted Avg: 0.92

## 🚀 How to Run
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook SupplierPerformance.ipynb
