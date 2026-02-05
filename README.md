# trader_sentiment_analysis
# ds_niyati_sharma
# 📊 Trader Behavior vs Market Sentiment – Data Science Assignment

This repository contains my solution to the Data Science assignment by the Web3 Trading Team. The task explores the relationship between trader behavior (profitability, leverage, size) and market sentiment (Fear, Greed, etc.).

---

## 📁 Project Structure
ds_niyati_sharma/
├── notebook_1.ipynb # Main Colab notebook with full analysis

├── csv_files/ # Processed data files

│ └── summary_stats_by_sentiment.csv

| └──summary_stats_by_sentiment.csv

| ├──fear_greed_index.csv

├── outputs/ # Graphs and visualizations

│ ├── pnl_by_sentiment.png

│ ├── timeseries_pnl.png

│ ├──heatmap_correlation.png

| ├──timeseries_sizeusd.png

| ├──timeseries_executionprice.png

| ├──timeseries_dualaxis.png

| ├──scatter_leverage_pnl.png

| ├──start_position_log_hist.png

├── ds_report.pdf # Final report with insights

└── README.md # This file

---

## 📌 Objective

To investigate how trading behavior ( Closed PnL, Start Position, trade size) aligns or diverges from crypto market sentiment. The goal is to identify patterns that inform smarter trading strategies.

---

## 📊 Datasets Used

1. **Market Sentiment (Fear & Greed Index)**  
   Columns: `Date`, `Classification` (Fear, Greed, etc.)

2. **Trader Behavior Data**  
   Columns: `Account`, `Execution Price`, `Size USD`, `Side`, `Timestamp`, `Closed PnL`, `Start Position`, etc.

---

## 🔍 Key Analyses

- 📉 **Descriptive statistics** of `Closed PnL`, `Start Position`, and `size` across sentiments  
- 🧪 **Statistical tests** (t-test & Mann–Whitney U) comparing Fear vs Greed performance  
- 📈 **Time series analysis** of average trade size, fee, and leverage  
- 📊 **Correlation heatmaps** and scatterplots  

---

## 📷 Key Visualizations

- Boxplot: `Closed PnL` by Sentiment  
- Histogram: Start Position by Sentiment  
- Time Series: Avg. Trade Size Over Time  
- Heatmap: Correlation between features  
- Scatterplot: Leverage (Start Position) vs Profitability

_All visualizations are saved in the `/outputs/` folder._

---

## 🧠 Insights Summary

- Traders tend to use **higher leverage** and are **more profitable during Greed**.
- **Significant statistical difference** in `Closed PnL` between Fear and Greed (p ≪ 0.05).
- Trade size and fee are **highly correlated** (r ≈ 0.75).
- Some accounts profit even during Fear, indicating possible contrarian strategies.

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
- Google Colab
- GitHub

---

## 📎 Instructions to Run

1. Open `notebook_1.ipynb` in Google Colab  
2. Mount Google Drive to access input files  or try uploading data files provided
3. Ensure the following folder structure is maintained  
4. All outputs and plots will be saved to `/outputs/`

---

## 📬 Contact

- Author: `NIYATI SHARMA`
- Email: `sharmaniyati1010@gmail.com`
