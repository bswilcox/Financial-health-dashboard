# 📊 Financial Health Dashboard

A data-driven project that analyzes the financial health of major companies using key financial ratios, time-series visualizations, and interactive dashboards. Built with Python, Pandas, Plotly, and Tableau.

---

## 📁 Project Structure

financial-health-dashboard/
├── data/
│ ├── raw/ # Original financial statements from APIs/sources
│ └── cleaned/ # Cleaned CSVs (e.g., AAPL_balance_sheet_clean.csv)
├── notebooks/
│ ├── 01_ingestion_and_cleaning.ipynb
│ ├── 03_eda_and_metrics.ipynb
│ └── 04_visualizations.ipynb
├── dashboard/
│ └── tableau_dashboard.twbx
├── sql/ # Optional SQL modeling (if needed)
│ ├── create_tables.sql
│ └── financial_ratios.sql
├── README.md
├── requirements.txt
└── presentation.pdf # (Optional) Slide deck summarizing key insights

---

## 📌 Key Features

- 📥 **Data Ingestion**: Pulls and parses raw balance sheets, income statements, and cash flow data.
- 🧹 **Data Cleaning**: Standardizes date formats, removes missing values, and formats numerical values.
- 📈 **Ratio Calculation**: Computes financial health ratios like:
  - Current Ratio
  - Debt-to-Equity
  - Return on Equity
  - Gross Margin, etc.
- 📊 **Visualizations**: Interactive Plotly graphs comparing companies over time.
- 📉 **Tableau Dashboard**: Clean, intuitive summary of financial metrics.

---

## 🏗 Technologies Used

- **Python** (Pandas, Plotly, NumPy)
- **Jupyter Notebooks**
- **Tableau**
- **Git & GitHub**
- *(Optional)* SQL for modeling

---

## 🧠 Insights & Storytelling

> Coming soon: A full data story outlining how AAPL, JPM, and JNJ compare across financial ratios over time, and what trends suggest about their financial health.

---

## 🧰 Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/bswilcox/financial-health-dashboard.git
   cd financial-health-dashboard
Create a virtual environment (optional but recommended):


python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
Install dependencies:


pip install -r requirements.txt
Run the notebooks in order:

01_ingestion_and_cleaning.ipynb

03_eda_and_metrics.ipynb

04_visualizations.ipynb

📬 Contact
Created by Brennon Wilcox — feel free to reach out!


---
