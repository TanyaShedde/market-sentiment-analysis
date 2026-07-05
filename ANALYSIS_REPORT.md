# Analysis Report: Methodology & Insights

## 🛠️ Methodology & Technical Approach

The analysis was executed through a structured, four-phase data science pipeline:

*   **Data Aggregation & Integration:** 

Engineered a unified dataset by merging raw, granular trade execution logs with macro-environmental daily Fear & Greed sentiment indexes.

*   **Feature Engineering:** 

Leveraged Pandas to group and compress row-level transactional data into daily performance matrices.
Calculated key performance indicators (KPIs) including Daily Net PnL, Win Rate, and Average Position Size.

*   **Statistical Evaluation:** 

Conducted exploratory data analysis (EDA) using Seaborn and Matplotlib to isolate behavioral variables.
visualize how market psychology directly influences retail risk management and profitability.

---

## 📊 Key Insights

Based on the generated charts and tables, the data revealed the following observations regarding trader performance and behavior:

*   **Average PnL per Trade:** It was observed that traders operating during periods of "Extreme Greed" achieve the highest average PnL per trade.
*   **Overall Win Rate:** Similarly, traders exhibit the highest overall win rate when the market sentiment is classified as "Extreme Greed."
*   **Trade Frequency by Sentiment:** Interestingly, when analyzing trade frequency, the highest total number of trades occurs during periods of heightened "Fear," indicating that traders execute more transactions when they are fearful.
