# Trader Performance vs Market Sentiment Analysis

## Objective
This project analyzes how market sentiment (Fear/Greed) influences trader behavior and performance on Hyperliquid.  
The goal is to identify behavioral patterns and derive actionable trading insights.

---

## Datasets Used
1. **Fear & Greed Index**
   - Contains daily market sentiment classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral).

2. **Historical Trader Data**
   - Includes trade-level information such as account, side (BUY/SELL), trade size, execution price, and Closed PnL.

---

## Methodology
- Loaded and cleaned both datasets.
- Converted timestamps and aligned data at daily granularity.
- Merged trader data with market sentiment.
- Performed exploratory analysis using visualizations and aggregated metrics.

---

## Key Analyses
- Trader performance (Closed PnL) across sentiment states
- Trade activity comparison by sentiment
- Long vs Short behavior analysis
- Trade size analysis as a proxy for risk appetite

---

## Key Insights
- Trader profitability varies across market sentiment phases.
- Trade frequency and position direction change depending on market mood.
- Trade size patterns suggest sentiment-driven risk behavior.

---

## Strategy Recommendations
- Reduce position size during extreme sentiment phases to control risk.
- Increase participation only during sentiment conditions associated with stronger performance.

---

## Conclusion
Market sentiment significantly influences trader behavior and performance.  
Sentiment-aware strategies can help improve decision-making and risk management.