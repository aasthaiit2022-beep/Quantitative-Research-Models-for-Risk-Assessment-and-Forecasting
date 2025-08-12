# 📊 Quantitative Research Project

This repository contains a collection of **quantitative finance and data analysis** tasks, covering topics from financial instrument pricing to credit risk modeling and market forecasting.

Each task is self-contained with its own dataset and Jupyter notebook, making it easy to follow and reproduce the results.

---

## 📌 **Task 1 — Pricing Model Prototype**
**Folder:** `Pricing_Model`  
**Files:** 
- `Pricing_Model_Prototype.ipynb`
- `Nat_Gas.csv`

This task implements a **pricing model** for a financial instrument using natural gas price data.  
It demonstrates:
- Data preprocessing
- Feature engineering
- Simple pricing computation logic

---

## 📌 **Task 2 — Natural Gas Price Forecast**
**Folder:** `Natural_Gas_Forecast`  
**Files:**
- `Nat_Gas(1).csv`
- `Natural_gas_price_estimate.ipynb`
- `Natural Gas Price History.png`

This analysis explores **historical natural gas prices** and forecasts future trends using a **linear trend model**.

**Key Outputs:**
- Historical price visualization
- 1-year price forecast  
![Natural Gas Price History](Natural%20Gas%20Forecast/Natural%20Gas%20Price%20History.png)

---

## 📌 **Task 3 — Probability of Default (PD) Model**
**Folder:** `PD_Model`  
**Files:**
- `Probability_of_Default.ipynb`
- `Task 3 and 4_Loan_Data.csv`

This task builds a **logistic regression model** to estimate the **Probability of Default** for borrowers, based on loan data.

Key concepts:
- Logistic regression
- Expected loss computation  
- Ensuring no negative costs in output

---

## 📌 **Task 4 — FICO Score Bucketing**
**Folder:** `FICO_Bucketing`  
**Files:**
- `FICO_distribution.ipynb`
- `FICO distribution.png`
- `Task 3 and 4_Loan_Data.csv`
This task segments **FICO scores** into risk categories using **SSE-based bucketing**.  
Categories include:
- Poor
- Fair
- Good
- Very Good
- Excellent

**Output Plot:**  
![FICO Distribution](FICO%20bucketing/FICO%20distribution.png)

---

## ⚙️ **Tech Stack**
- Python (pandas, numpy, matplotlib, scikit-learn)
- Jupyter Notebooks
- Data visualization

---

## 🚀 **How to Run**
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
