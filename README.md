# 📊 Trader Performance vs Market Sentiment

## 🧠 Objective
This project analyzes how market sentiment (Fear/Greed) affects trader behavior and performance using real trading data.

---

## 📂 Datasets Used

### 1. Market Sentiment Data
- Columns: Date, Classification (Fear / Greed)

### 2. Trader Data
- Includes: Account, Execution Price, Size, Side, Timestamp, Closed PnL, etc.

---

## ⚙️ Data Preparation

- Loaded both datasets using pandas
- Checked for missing values and duplicates (none found)
- Converted timestamps to date format
- Merged datasets on Date

---

## 📈 Key Metrics

- Daily Profit & Loss (PnL)
- Win Rate (profitable trades %)
- Trade Frequency
- Average Trade Size

---

## 📊 Analysis

### 🔹 Performance vs Sentiment
- Extreme Greed → Highest average PnL (~67.89)
- Extreme Fear → Lowest performance
- Win rate highest in Extreme Greed (~46%)

### 🔹 Behavior Changes
- Trading activity varies across sentiment types
- Emotional markets (Fear/Greed) influence decisions

---

## 👥 Trader Segmentation

- Frequent Traders → High trading activity
- Infrequent Traders → Lower participation

---

## 💡 Key Insights

1. Traders perform best during Extreme Greed
2. Fear negatively impacts trading performance
3. Market sentiment strongly influences behavior

---

## 🚀 Strategy Recommendations

- During Fear → Reduce trading activity
- During Extreme Greed → Apply risk control to avoid overconfidence

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib

---

## ▶️ How to Run

1. Clone the repository
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib
