# Trader Sentiment Analysis Assignment

This repository contains a data science analysis project submitted for the `[Position Name/Company Name]` application.

## 1. Objective

The objective of this assignment is to analyze historical trader data from Hyperliquid against the Bitcoin Market Sentiment (Fear & Greed Index) to identify patterns in trader behavior, profitability, and activity relative to market sentiment.

## 2. Repository Structure

The repository follows the standardized submission format:

ds_<name>/ ├── notebook_1.ipynb # Google Colab notebook with all Python code ├── csv_files/ │ └── processed_trade_data.csv # Cleaned and merged data output ├── outputs/ │ ├── pnl_by_sentiment.png │ ├── volume_by_sentiment.png │ ├── trade_count_by_sentiment.png │ ├── side_by_sentiment.png │ └── pnl_vs_sentiment_timeline.png ├── ds_report.pdf # Final summarized insights and explanations └── README.md # This file


## 3. How to Run

1.  **Google Colab:** The primary analysis is contained in `notebook_1.ipynb`.
2.  **Data:** The notebook assumes the original `historical_data.csv` and `fear_greed_index.csv` files are present in the same runtime environment.
3.  **Execution:** Running all cells in the notebook will perform the analysis and generate all files for the `outputs/` and `csv_files/` directories.
4.  **Report:** The `ds_report.pdf` contains a full summary and an explanation of the findings.