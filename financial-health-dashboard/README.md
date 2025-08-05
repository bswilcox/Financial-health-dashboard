
# Financial Health Dashboard

[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Project Overview

This project analyzes the financial health of major companies across three sectors by collecting, cleaning, and visualizing their financial statements over multiple years. Using Python and Tableau, it extracts key financial ratios to provide insights into profitability, liquidity, and leverage.

---

## Data Sources

- Financial statements downloaded using the [yfinance](https://pypi.org/project/yfinance/) Python library.
- Companies analyzed: Apple (AAPL), JPMorgan Chase (JPM), and Johnson & Johnson (JNJ).

---

## Repository Structure

financial-health-dashboard/
├── data/
│ ├── raw/ # Raw downloaded CSVs from yfinance
│ └── cleaned/ # Cleaned and processed data ready for analysis
├── notebooks/
│ ├── 01_ingestion_and_cleaning.ipynb # Data ingestion and cleaning scripts
│ ├── 02_eda_and_metrics.ipynb # Financial ratios calculation and EDA
│ └── 03_visualizations.ipynb # Interactive visualizations with Plotly
├── dashboard/
│ └── tableau_dashboard.twbx # Tableau dashboard workbook
├── README.md
├── requirements.txt
└── presentation.pdf

yaml
Copy
Edit

---

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Recommended: a Jupyter notebook environment (e.g., JupyterLab, VS Code, or Google Colab)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/financial-health-dashboard.git
cd financial-health-dashboard
Install required packages:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Run the notebooks sequentially to reproduce the analysis and visualizations:

Data Ingestion and Cleaning:
notebooks/01_ingestion_and_cleaning.ipynb
Downloads raw financial data using yfinance and cleans it.

Exploratory Data Analysis and Metrics:
notebooks/02_eda_and_metrics.ipynb
Calculates key financial ratios and performs exploratory analysis.

Visualizations:
notebooks/03_visualizations.ipynb
Creates interactive charts to explore financial health trends.

Key Financial Ratios Included
Net Profit Margin

Return on Equity (ROE)

Debt to Equity Ratio

Current Ratio

Insights
For a detailed analysis of the financial data and key findings, see the INSIGHTS.md file or the presentation.pdf.

Skills Demonstrated
Data scraping with Python and yfinance

Data cleaning and transformation with pandas

Financial ratio calculation and analysis

Interactive visualization with Plotly Express

Dashboard creation with Tableau

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
Created by [Brennon Wilcox] - feel free to reach out via [brennonsw@gmail.com].

