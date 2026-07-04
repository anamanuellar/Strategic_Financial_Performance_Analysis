# 📊 Financial Performance Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Lib-Pandas%20%7C%20Plotly%20%7C%20Seaborn-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Project Overview
This project delivers a comprehensive **diagnostic of the financial health** of a multinational corporation. By analyzing Sales, Costs, and Profitability data, it moves beyond descriptive metrics to provide prescriptive insights for strategic decision-making.

The analysis focuses on bridging the gap between raw financial data and actionable business strategies, addressing efficiency, seasonality, and risk management.

## 🎯 Key Business Questions
* Is the business growing in terms of revenue and profit?
* Does revenue growth translate into operational efficiency?
* How dependent is profitability on exceptional, high-value transactions (outliers)?
* Which products are structurally efficient versus volatile?

---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Manipulation (ETL):** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn (for statistical distribution), Plotly (for interactive dashboards)
* **Environment:** Jupyter Notebook / Google Colab

---
## 📂 Dataset
The data used in this project is the **Company Financials** dataset, available publicly on Kaggle. 

* **Source:** [Kaggle - Company Financials Dataset](https://www.kaggle.com/datasets/atharvaarya25/financials/data)
* **Rows:** 700
* **Columns:** 16

## ⚙️ Methodology & Workflow

The analysis follows a structured pipeline:

### 1️⃣ Data Engineering (ETL & Validation)
* Inspection of data structure and handling currency-formatted strings.
* **Scenario Testing:** Strategic treatment of missing values in the `Profit` column to avoid statistical bias.
* **Chronological Fixing:** Correcting month ordering to ensure accurate time-series plotting.

### 2️⃣ Global Performance Analysis
* Evaluation of Sales and Profit evolution over time.
* Profit Margin analysis to assess the real efficiency of revenue growth.

### 3️⃣ Risk Assessment (Outlier Analysis)
* Application of the **IQR Method** to detect outliers.
* **Dual Perspective:** Comparing financial metrics *with* and *without* outliers to understand the impact of "whale" clients versus recurring operational stability.

### 4️⃣ Profitability Drivers
* Product-level segmentation to identify structurally efficient products versus those dependent on high-value contracts.

---

## 📈 Key Findings & Insights

1.  **Revenue vs. Profit:** Revenue growth does not consistently translate into proportional profit growth, indicating variable operational costs.
2.  **The "Whale" Effect:** Profitability is partially driven by exceptional, high-value transactions. Removing these outliers distorts the business reality, so they are treated as a core part of the strategy.
3.  **Product Volatility:** Some products demonstrate stable operational margins, while others fluctuate heavily based on large, sporadic contracts.

---

## 🚀 How to Run this Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ana-manuella/financial-performance-analysis.git](https://github.com/ana-manuella/financial-performance-analysis.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn plotly
    ```
3.  **Run the Notebook:**
    ```bash
    jupyter notebook "Financial_Performance_Analysis.ipynb"
    ```

---

## 👨‍💻 Author

**Ana Manuella Ribeiro**

*Finance professional building automation and analytics capability*

[LinkedIn](https://www.linkedin.com/in/anamanuellar)
