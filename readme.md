# Web3 Trading Team – Data Science Assignment

## 📌 Project: Trader Behavior vs Market Sentiment Analysis

### 👤 Candidate: Abhay Mittal

---

## 📁 Repository Structure

```
ds_abhay_mittal/
├── notebook_1.ipynb               # Main Colab notebook with full analysis
├── csv_files/                     # Contains intermediate or processed data
│   └── processed_agg_day.csv
├── outputs/                       # Visualizations from EDA and feature engineering
│   └── avg_pnl_sentiment.png
│   └── volume_sentiment.png
│   └── leverage_sentiment.png
├── ds_report.pdf                  # PDF summary of findings and insights
└── README.md                      # Project overview and instructions
```

---

## 🚀 Project Objective

To analyze the alignment between **trading behavior** and **market sentiment (Fear/Greed)** using:

* A **Bitcoin Sentiment Index** dataset.
* A **Hyperliquid Historical Trade Dataset**.

Goal: Extract actionable insights to identify patterns in profitability, leverage, and trading behavior under varying sentiment conditions.

---

## 🧠 Key Analysis Steps

1. **Data Cleaning & Parsing**:

   * Parsed timestamps from both datasets.
   * Merged datasets on `date`.

2. **Feature Engineering**:

   * Aggregated metrics per day: PnL, volume, fees.
   * Calculated leverage proxy: USD volume vs position size.

3. **Visualizations**:

   * Boxplots and bar charts to compare sentiment-based behavior.

4. **Insights & Strategy Suggestions**:

   * Found aggressive leverage and higher volume during 'Greed'.
   * Suggested sentiment-driven trading adaptations.

---

## 🛠️ How to Run

1. Open the `notebook_1.ipynb` in Google Colab.
2. Ensure all CSV files are placed in the `csv_files/` folder.
3. All output images will be generated and saved under `outputs/`.

---

## 📄 Submission Notes

* All required files are included and structured as per the Web3 Trading Team's guidelines.
* Analysis is reproducible and code is well-commented.
* Insights are summarized in `ds_report.pdf`.

---

Thank you for the opportunity!

