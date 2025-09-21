Sure! Here’s your README **without the Conclusion section**, keeping it clean and minimal:

---

# 📊 Mutual Fund Analysis & Visualization

This project highlights how data science and visualization can be combined to **discover the best-performing mutual fund schemes** with a balance of **returns and risk**.

 **Technologies Used:** Python (Pandas, Scikit-learn), MS Excel, Power BI
 **Dataset Size:** 2500+ mutual fund schemes → filtered to **Top 30 funds**

---

## 🎯 Objective

To analyze a large mutual fund dataset, apply **data-driven ranking techniques**, and showcase insights through an **interactive Power BI dashboard**, making investment choices easier and smarter.

---

##  Python Data Workflow

I began with raw data containing 2500+ schemes and applied a systematic pipeline in Python.
🔗 [View Python Script](https://github.com/notneerajsah/Mutual-Fund-Analyisis-top30-python-excel-powerBi/blob/main/Mutual%20Fund%20Analysis.ipynb)

### Step 1: Cleaning & Preparation

* Dropped irrelevant fields
* Handled blanks and inconsistencies
* Converted numeric columns (returns, AUM, expense ratio) into proper formats

### Step 2: Exploratory Data Analysis

* Summary statistics: mean, median, range, standard deviation
* Distribution analysis across fund type, risk grade, and age

### Step 3: Normalization

* Applied **MinMaxScaler** to bring all metrics onto a comparable scale
* Ensured fair comparison between high-return and low-cost funds

### Step 4: Scoring & Ranking Model

Ranking formula considered:

* Strong 3-year returns
* Reasonable expense ratio
* Stable track record with 1Y positive return
* Moderate fund age (not too new, not too old)

### Step 5: Top 30 Funds

Final list of top 30 funds exported for further analysis.
🔗 [Excel File – Top 30](https://github.com/notneerajsah/Mutual-Fund-Analyisis-top30-python-excel-powerBi/blob/main/top_30_mutual_funds.xlsx)

---

## 📊 Power BI Dashboard – Fund Insights

Processed outputs were then integrated into **Power BI** to create a visual dashboard.
🔗 [PBIX File](https://github.com/notneerajsah/Mutual-Fund-Analyisis-top30-python-excel-powerBi/blob/main/Mutual%20Fund%20Dashboard.pbix)

### Dashboard Highlights

* Interactive Filters: Category, AMC, Risk, Rating, Fund Type
* Key Visuals:

  * AUM breakdown by category (Equity, Debt, Hybrid, etc.)
  * SIP vs Lumpsum investment trends
  * Expense ratio benchmarking across strategies
  * Donut chart for 3-year return distribution
  * AMC-wise performance and market share
  * Fund manager AUM leaderboard

---

##  Key Insights

| Category           | Finding                                               |
| ------------------ | ----------------------------------------------------- |
| Market Trends      | Equity funds dominate with AUM ₹1.35M Cr              |
| Fund Managers      | Highest AUM handled by Vivek Sharma – ₹7.3M Cr        |
| Cost Efficiency    | Index funds show lowest average expense ratio (0.26%) |
| Top Performer (1Y) | Bank of India MF with 14.4% returns                   |
| Investment Modes   | Avg SIP \~₹528/month, Avg lumpsum min \~₹3,050        |
| 3-Year Returns     | Equity: 37.84%, Hybrid: 14.25%                        |

---

## Dashboard Preview

![Mutual Fund Dashboard](https://github.com/notneerajsah/Mutual-Fund-Analyisis-top30-python-excel-powerBi/blob/main/Mutual%20Fund%20Dashboard%20.png)

---

## Repository Contents

| File                         | Purpose                              |
| ---------------------------- | ------------------------------------ |
| `top_30_mutual_funds.xlsx`   | Final ranked list of 30 mutual funds |
| `Mutual Fund Dashboard.pbix` | Interactive Power BI dashboard       |
| `Mutual Fund Dashboard.png`  | Dashboard preview image              |

---

