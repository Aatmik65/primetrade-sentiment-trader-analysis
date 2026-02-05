# Primetrade.ai – Data Science Intern Assignment

## Objective
Analyze trader behavior and performance under different Bitcoin market sentiment conditions (Fear vs Greed).

## Datasets
- Bitcoin Fear & Greed Index
- Hyperliquid trader-level execution data

## Methodology
- Cleaned and time-aligned both datasets at the daily level
- Engineered key trading metrics (PnL, win rate, leverage, trade frequency)
- Compared trader performance and behavior across Fear and Greed periods
- Segmented traders based on leverage and activity levels

## Key Insights
- Trader PnL volatility is significantly higher during Fear periods
- Average leverage and trade frequency increase during Greed phases
- Win rates improve slightly during Greed, but with higher downside risk
- High-leverage traders experience deeper drawdowns during Fear

## Strategy Recommendations
1. Reduce leverage exposure during Fear periods to limit drawdowns
2. Allow selective leverage expansion during Greed for consistently profitable traders

## How to Run
1. Clone the repository
2. Place datasets inside the `data/` folder
3. Open `Primetrade_Data_Analysis.ipynb.`
4. Run all cells

## Tools Used
- Python
- Pandas
- Matplotlib
- NumPy
