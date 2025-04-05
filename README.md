# Financial-Data-Analysis
Project on fraud detection using credit card transaction data
# 🧠 Financial Data Fraud Detection with Machine Learning

This project focuses on analyzing credit card transaction data to detect fraudulent activities using machine learning techniques. It includes data preprocessing, visualization, model building, and evaluation — all inside a single Jupyter Notebook.

---

## 📌 Project Overview

- **Dataset Used**: `creditcard.csv` (contains 284,807 transactions with 492 frauds)
- **Objective**: Detect fraudulent transactions from a highly imbalanced dataset
- **Tech Stack**: Python, Pandas, Matplotlib, Seaborn, Scikit-learn, SQLite3

---

## 🚀 Key Steps Performed

1. **Data Loading & Cleaning**
   - Removed duplicates and checked missing values
   - Normalized and prepared the features

2. **SQL Integration**
   - Stored dataset in SQLite3 and queried basic stats

3. **EDA (Exploratory Data Analysis)**
   - Visualized transaction amount distribution
   - Compared fraud vs. non-fraud patterns

4. **Model Building**
   - Used Random Forest Classifier for fraud prediction
   - Performed stratified Train-Test Split

5. **Evaluation Metrics**
   - Accuracy: **99.9%**
   - Precision: **96%**
   - Recall: **73%**
   - F1 Score: **83%**
   - Visualized Confusion Matrix

---

## 📁 Files Included

- `Financial_data_analysis.ipynb`: Full Jupyter Notebook with code, visuals, and results
- `creditcard.csv`: Dataset (not uploaded due to size, please download manually)

---

## 🛠️ How to Run the Project
### 🔧 Requirements
Make sure you have the following installed:

pip install pandas matplotlib seaborn scikit-learn
## 📁 Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Aishwarya23mc/financial-data-analysis.git
2.Open the Jupyter Notebook
3.Run the Notebook Open Financial_data_analysis.ipynb and run all cells.
4.✅ Explore the Results
View EDA plots, model performance, confusion matrix, etc.
Detect fraudulent transactions using the trained model.


