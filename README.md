# Personal Expense Analyzer 📊

### Python | Pandas | NumPy | Matplotlib | Google Colab

## 📌 Project Overview

The Personal Expense Analyzer is a Python-based data analysis project designed to explore, clean, and analyze personal expense transactions.

The project uses Pandas and NumPy to process transaction data, identify spending patterns, calculate financial KPIs, and generate visual insights.

The objective is to demonstrate practical data analytics skills through data cleaning, exploratory data analysis (EDA), aggregation, and visualization.

**Note:** This project uses synthetically generated transaction data for learning and analytical practice. It does not contain actual personal financial records.

## 🎯 Project Objectives

- Generate and inspect a transaction dataset.
- Identify and handle missing values and duplicate records.
- Convert and validate date and numeric columns.
- Analyze expenses across categories and months.
- Compare spending across payment methods.
- Calculate financial KPIs.
- Visualize spending patterns and trends.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming and analysis |
| Pandas | Data cleaning and manipulation |
| NumPy | Synthetic data generation |
| Matplotlib | Data visualization |
| Google Colab | Notebook environment |

## 📂 Repository Structure

```text
Personal-Expense-Analyzer/
│
├── README.md
├── Personal_Expense_Analyzer.ipynb
└── cleaned_expenses.csv
```

## 📁 Dataset Description

The dataset contains expense transactions generated using NumPy.

- Original generated transactions: 100
- Additional duplicate record: 1
- Records after cleaning: 98
- Analysis period: January–June 2026
- Final dataset columns: 11

### Dataset Columns

| Column | Description |
|---|---|
| Date | Transaction date |
| Category | Expense category |
| Amount | Transaction amount |
| Payment_Method | Payment method |
| Description | Transaction description |
| Year | Transaction year |
| Month | Month number |
| Month_Name | Month name |
| Year_Month | Year and month |
| Day_Name | Day of the week |
| Day | Transaction date without time |

## 🧹 Data Cleaning Process

The following data cleaning operations were performed:

1. Inspected dataset structure using `head()`, `tail()`, `info()` and `describe()`.
2. Identified missing values using `isnull().sum()`.
3. Identified duplicate records using `duplicated()`.
4. Converted dates using `pd.to_datetime()`.
5. Converted expense amounts using `pd.to_numeric()`.
6. Removed duplicate records using `drop_duplicates()`.
7. Removed records with missing dates or amounts using `dropna()`.
8. Replaced missing categories and payment methods with `Unknown`.
9. Extracted Year, Month, Month_Name, Year_Month, Day_Name and Day.

## 📊 Exploratory Data Analysis

The project includes:

- Total and average expense calculations.
- Minimum and maximum transaction analysis.
- Category-wise spending analysis.
- Monthly spending trends.
- Daily spending analysis.
- Weekday spending analysis.
- Payment-method analysis.
- Category and monthly summary reports.

## 📈 Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Transactions | 98 |
| Total Expenditure | ₹155,153 |
| Average Transaction | ₹1,583.19 |
| Minimum Transaction | ₹51 |
| Maximum Transaction | ₹2,994 |
| Active Spending Days | 74 |

## 🔍 Key Analytical Findings

**1. Category-wise Spending**

- Highest spending category: Bills
- Total Bills expenditure: ₹26,468
- Education expenditure: ₹24,912

**2. Monthly Spending**

- Highest spending month: January 2026
- January expenditure: ₹31,374
- Lowest spending month: April 2026
- April expenditure: ₹17,004

**3. Payment Method Analysis**

- Highest expenditure by payment method: Credit Card
- Credit Card expenditure: ₹46,637
- Cash expenditure: ₹42,938

These findings are based on the cleaned synthetic dataset.

## 📉 Visualizations

The project generates the following visualizations using Matplotlib:

- Total Spending by Category (Horizontal Bar Chart)
- Monthly Spending Trend (Line Chart)
- Share of Spending by Category (Pie Chart)
- Daily Spending Trend (Line Chart)

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Open `Personal_Expense_Analyzer.ipynb` in Google Colab or Jupyter Notebook.
3. Upload `cleaned_expenses.csv` if you want to inspect the exported dataset separately.
4. Run the notebook cells sequentially.

**Note:** The original notebook generates its own sample dataset and reads `personal_expenses.csv`. Run the data-generation cells first, or update the CSV loading path when using the separately uploaded cleaned dataset.

## 📚 Skills Demonstrated

- Python programming
- NumPy random data generation
- Pandas DataFrame operations
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- GroupBy and aggregation
- Date and time analysis
- KPI calculation
- Data visualization
- CSV export and reporting

## 👨‍💻 Author

**Jeevtesh Singh**

Aspiring Data Analyst | SQL | Excel | Python | Power BI

GitHub: https://github.com/JeevteshSingh-dev

LinkedIn: https://linkedin.com/in/jeevtesh-singh-37091b2aa

---

*This project was developed as part of my practical learning journey in Data Analytics.*
