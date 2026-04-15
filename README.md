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

## 📁 Project Structure & Documentation
Properly organized repository for high-level data accessibility:

- **[Insights & Summary](./Insights/summary.md)**: A detailed executive summary of findings and strategy performance.
- **[Visualizations Folder](./visualizations/)**: Contains all generated charts (Equity Curves, Sentiment Analysis, etc.).
- **[Raw CSV Data](./DataSets/)**: The source files used for this analysis.
- **[Full Code Of The Assignment](./Code/)`trading_analysis.ipynb`**: The full Python/Pandas source code and data cleaning pipeline.

---

## 💡 Top Insights
1. **The "Fear" Alpha:** The strategy generated the highest total profit during market "Fear" periods, validating a contrarian approach.
2. **Profitability Peak:** While total volume was highest in Fear, the average profit per trade peaked during "Extreme Greed."
3. **Asset Concentration:** High dependency on specific tickers like **@107** and **HYPE**, which contributed significantly to the total PnL.

---

## 🚀 How to Run
1. Clone the repository.
2. Ensure `historical_data.csv` and `fear_greed_index.csv` are in the `/data` folder.
3. Open `trading_analysis.ipynb` in Google Colab or Jupyter Notebook and run all cells.
