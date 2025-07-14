# 📊 Data Science Assignment – Web3 Trading Team


Welcome! This repository contains my submission for the Web3 Trading Team's Data Science assignment. The goal was to analyze the relationship between trader behavior and Bitcoin market sentiment using historical datasets.

---

## 🗂 Folder Structure

ds_name/
├── notebook_1.ipynb # Main Colab notebook with full analysis
├── csv_files/ # Intermediate or processed CSVs
│ └── merged_data.csv
├── outputs/ # Visual outputs and plots
│ ├── sentiment_dist.png
│ ├── pnl_vs_sentiment.png
│ └── volume_by_sentiment.png
├── ds_report.pdf # Final written report in PDF format
└── README.md # This file


---

## 📁 Datasets Used

1. **Bitcoin Fear and Greed Index**  
   - Columns: `timestamp`, `value`, `classification`, `date`  
   - Describes market sentiment on a daily basis as either *Fear* or *Greed*.

2. **Hyperliquid Trader Data**  
   - Columns include: `Execution Price`, `Size USD`, `Side`, `Direction`, `Closed PnL`, etc.  
   - Records anonymized trading activity.

---

## 🎯 Objective

To explore how trading behavior (profitability, leverage, volume, direction) aligns or diverges from overall market sentiment (Fear vs Greed). The focus was on identifying actionable patterns that may inform smarter trading strategies.

---

##  Key Insights

- **Profitability**: Trades during Greed periods had higher volatility; Fear trades were more controlled.
- **Volume**: Higher during Fear — potentially due to stop-losses or emotional trading.
- **Trade Direction**: Short trades were more common in Fear; longs during Greed.
- **Leverage Use**: Varies with sentiment; lower on average during Fear.

All insights are supported by visualizations and data exploration inside the notebook.

---

## 🔧 How to Run

1. Open `notebook_1.ipynb` via Google Colab  
   [ Click to open](https://colab.research.google.com/drive/1EjpFFoy5MgHb3zHnyTeZNjIDMBLPqm4G?usp=sharing)

2. Datasets are automatically loaded from shared Drive or local folder.

3. Outputs are saved to:
   - `csv_files/` for cleaned datasets
   - `outputs/` for plots and graphs

---

## 📄 Report

The final summarized analysis is available in [`ds_report.pdf`](./ds_report.pdf). It includes:

- Overview of datasets and methods
- Exploratory Data Analysis (EDA) summary
- Key findings and visual insights
- Strategic takeaways for trading
- Deliverables checklist

---

## 🔗 Links

- 🔬 Google Colab Notebook: [View Notebook](https://colab.research.google.com/drive/1EjpFFoy5MgHb3zHnyTeZNjIDMBLPqm4G?usp=sharing)
- 📦 GitHub Repository: https://github.com/123sajid/ds_sajid

---

##  Submission Complies With

- Folder naming and structure   
- Colab notebook access set to  
- Report in PDF format 
- GitHub repository updated   

