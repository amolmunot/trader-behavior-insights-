# Does "Buy the Fear, Sell the Greed" Work?
### A Data-Driven Analysis of Trader Behavior

This project analyzes Hyperliquid trader data against the "Fear & Greed Index" to test a common piece of trading wisdom: "Buy the fear, sell the greed." My goal was to move beyond assumptions and find the *actual* data-backed patterns that drive profitability.

## 🚀 Key Findings & Core Insight

My analysis revealed a counter-intuitive insight. The key differentiator for profitability wasn't buying fear, but rather **how different traders behaved during market euphoria**.

1.  **"Bad" Traders Fight the Trend:** Unprofitable traders (bottom 25% by win-rate) suffer their worst losses (avg. PnL of **-$206**) on 'Extreme Greed' days. The data shows this is because they are **aggressively opening short positions (85.2% of their activity)**, trying to time the market top.

2.  **"Smart Money" Takes Profit:** In contrast, the top 25% of traders achieved their highest average PnL (**$445**) on 'Neutral' days. Their strategy was clear: they were **overwhelmingly closing long positions (87.4% of their activity)**, demonstrating a disciplined profit-taking strategy.

3.  **The Average Trader:** The data *rejects* the initial hypothesis. On average, PnL was **statistically higher** during 'Greed' days than 'Fear' days (p-value: 3.24e-09).

## 📈 Recommended Strategy (Based on Data)

A simple "buy the dip" strategy is not supported by this data. A better, data-backed strategy is to **avoid opening short positions during periods of 'Extreme Greed'**, as this is the single biggest mistake unprofitable traders make. The "smart money" in this dataset wins by taking profits, not by trying to time the market top.

## 🛠️ How to Run

The full analysis is contained in the `Trader_Sentiment_analysis.ipynb` notebook.

1.  Clone the repository.
2.  Ensure you have the required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scipy`.
3.  The datasets (`historical_data.csv` and `fear_greed_index.csv`) are included in this repository and are loaded by the notebook.
4.  Run the cells sequentially to reproduce the analysis and visualizations.
