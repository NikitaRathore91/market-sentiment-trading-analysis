# 📈 Sentiment vs Trader Performance Analysis

This project analyzes the relationship between **market sentiment** and **trader performance**, using trade data and sentiment classification to uncover patterns in profitability, win rates, leverage behavior, and more.

---

## 📂 Project Structure

- `merged_df`: Combined dataset containing trade and sentiment data.
- Sentiment categories: `Extreme Fear`, `Fear`, `Neutral`, `Greed`, `Extreme Greed`.

---

## 📊 Key Analyses

### ✅ Missing Values
Checked for missing sentiment labels:
- Found **6 missing out of 211,224** total rows — negligible impact.

### 💰 PnL by Sentiment
Grouped trades by sentiment to calculate:
- Total count
- Mean (average) PnL
- Sum PnL

### 📉 Average Closed PnL by Sentiment
Visualized with a barplot to show average performance in each sentiment state.

### 🏆 Win Rate Analysis
Calculated win rate (percentage of profitable trades) across sentiments.

### 📦 Volatility by Sentiment
Measured standard deviation of PnL for each sentiment group to understand risk.

### 👤 Top Performing Accounts
Identified top 10 accounts with the highest average PnL under each sentiment.

### 📈 Leverage Behavior
Boxplot analysis of leverage distribution (via `Start Position`) across sentiments.

---

## 🛠️ Tech Stack

- **Python** (pandas, seaborn, matplotlib)
- **Jupyter Notebook**
- Data preprocessing, visualization, and aggregation techniques

---

## 📌 Insights Summary

- **Extreme Greed** has the highest average PnL.
- **Extreme Fear** shows high volatility and low win rate.
- Traders tend to be more profitable in **Fear** and **Greed** zones than in **Neutral**.
- Risk (leverage) patterns vary by sentiment, with more aggressive positions during sentiment extremes.

---

## 📎 Author

**[Your Name]**  
Feel free to reach out for questions or collaboration.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

