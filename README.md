# trading-sentiment-analysis
An end-to-end data analytics project using Pandas and Matplotlib to evaluate trading strategy efficiency and sentiment correlation. Featuring KPI tracking, risk assessment, and equity curve modeling.
# Crypto Trading & Market Sentiment Analysis 📈

An end-to-end data analytics project exploring the correlation between market sentiment (Fear & Greed Index) and trading profitability. This project analyzes over 100,000 trades to identify high-alpha opportunities based on market psychology.

## 📊 Key Performance Indicators (KPIs)
- **Total Net PnL:** $10,296,958.94
- **Win Rate:** 83.20%
- **Average Profit per Trade:** $98.62
- **Most Profitable Asset:** @107
- **Total Trades Analyzed:** 104,408

---

## 📁 Repository Structure
- **/data**: Raw historical trading data and Fear & Greed Index values.
- **/insights**: Generated CSV reports for monthly trends and sentiment performance.
- **/visualizations**: High-resolution charts including Equity Curves and Sentiment Correlation bars.
- `trading_analysis.ipynb`: Full Python/Pandas source code and data cleaning pipeline.

---

## 💡 Key Insights
1. **The "Fear" Alpha:** The strategy generated the highest total profit ($3.35M) during market "Fear" periods, validating a contrarian "buy the dip" approach.
2. **Profitability Peak:** While total volume was highest in Fear, the **Average Profit per Trade** peaked during "Extreme Greed" ($130.21), suggesting successful exit strategies.
3. **Asset Concentration:** Assets like **@107** and **HYPE** contributed significantly to the total PnL, highlighting the importance of asset selection in high-volatility environments.

---

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy)
- **Matplotlib & Seaborn** (Data Visualization)
- **Google Colab** (Development Environment)

---

## 🚀 How to Run
1. Clone this repository.
2. Ensure you have the files in the `/data` folder.
3. Run the `trading_analysis.ipynb` notebook in Google Colab or Jupyter.
