# Financial Ratio Analyzer (2021–2023)

A lightweight and interactive financial analysis project that calculates and visualizes key financial ratios from company statements over three years (2021–2023). Built entirely in **Python** using **Plotly** for interactivity and **Pandas** for analysis.

---

## Project Overview

This project provides a simple yet powerful interface for analyzing core financial ratios, including:
- Net Profit Margin
- Current Ratio
- Return on Equity (ROE)
- Debt-to-Equity Ratio
- Quick Ratio
- Return on Assets (ROA)
- Inventory Turnover

The ratios are visualized using an interactive Plotly line chart, which allows for hovering, zooming, and easy comparison across years.

---

## Tech Stack

- **Python 3**
- **Pandas** – Data manipulation
- **Plotly** – Interactive visualizations
- **OpenPyXL** – Excel integration

Optional tools (coming soon):
- **Streamlit** – For uploading and analyzing your own Excel files
- **fpdf2** / **reportlab** – For PDF summary report generation

---

## Folder Structure
```
Project - Financial-ratio-analyzer/
├── data/                      # Raw and cleaned data
│   └── financial_statements.xlsx
├── notebooks/                # Jupyter notebooks
│   └── 01_ratio_analysis.ipynb
├── visuals/                  # Chart output (if exported)
├── README.md
└── requirements.txt
```

---

## Power BI Attempt (Why We Pivoted)

The project initially included a Power BI dashboard. However, due to the following limitations, we decided to use Plotly instead:

- Power BI line charts were incorrectly aggregating values (e.g., "Count of ROE") despite column data types being set to decimals.
- Limitations around exporting visuals to GitHub or notebooks

As a result, we rebuilt everything in **Python using Plotly**, which offered more control, reproducibility, and shareability — perfect for open-source and data science portfolios.

---

## Features
- Clean and interactive multi-line trend chart (Plotly)
- Handles Excel input and reshaping
- Optional PDF report export (coming soon)
- Optional Streamlit UI (coming soon)

---

## Sample Output
> Note: Due to Kaleido rendering issues, we skipped auto-saving the chart to PNG. However, the notebook fully renders the interactive chart with `fig.show()`.

---

## How to Run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/01_ratio_analysis.ipynb
   ```
4. Open the chart cell and interact with the Plotly figure!

---

##  Future Enhancements
-  Add image export of Plotly chart
-  Generate auto PDF summary report
-  Let users upload their own Excel file via Streamlit app

---

## Author
**Romita Thally**  
Financial Analyst
[GitHub](https://github.com/RomitaUT)


