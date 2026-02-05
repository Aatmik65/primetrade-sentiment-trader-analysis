# Primetrade.ai – Data Science Intern Assignment

## Methodology
The analysis combines Bitcoin market sentiment data (Fear & Greed Index) with Hyperliquid trader-level execution data. 
Both datasets were cleaned, time-aligned at a daily level, and merged to enable sentiment-based performance analysis.

## Key Insights
1. Trader performance shows higher volatility during Fear days, with lower average win rates.
2. Leverage usage increases significantly during Greed periods, leading to higher PnL dispersion.
3. Frequent traders outperform infrequent traders during Greed phases but underperform during Fear.
4. High-leverage traders experience sharper drawdowns on Fear days.

## Strategy Recommendations
1. Reduce leverage exposure during Fear periods, especially for high-leverage traders.
2. Allow selective leverage expansion during Greed phases for consistently profitable traders.
