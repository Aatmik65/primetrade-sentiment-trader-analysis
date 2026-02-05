# Primetrade.ai – Data Science Intern Assignment

## Objective
Analyze trader behavior and performance under different Bitcoin market sentiment conditions (**Fear vs Greed**) using real trading data and the Bitcoin Fear & Greed Index.

---

## Datasets
- **Bitcoin Fear & Greed Index**  
  Provides daily market sentiment classification (Fear / Greed).

- **Hyperliquid Trader-Level Execution Data**  
  Contains trade-level details such as execution price, trade size, direction, timestamp, and realized profit/loss.

---

## Methodology
- Cleaned and preprocessed both datasets.
- Converted timestamps and aligned trading data with sentiment data at a **daily level**.
- Engineered key trading metrics, including:
  - Daily total PnL
  - Win rate
  - Average trade size
  - Trade frequency
- Compared trader performance and behavior across Fear and Greed market conditions.

---

## Key Insights
- Trader PnL volatility is significantly higher during **Fear** periods.
- **Greed** periods are associated with higher trading activity and larger average trade sizes.
- Win rates improve slightly during Greed, but with increased risk exposure.
- Fear periods show more conservative trading behavior and lower overall profitability.

---

## Strategy Recommendations
1. **Risk Control During Fear**  
   Reduce trade sizes and aggressive positioning during Fear-driven markets to limit downside risk.
2. **Selective Aggression During Greed**  
   Allow higher trading activity during Greed periods, supported by proper risk controls.

---

## Repository Contents
- `Primetrade_Data_Analysis.ipynb` – Full analysis notebook
- `Final_Insights_and_Strategy.md` – Summary of insights and strategies
- `Data.zip` – Contains required datasets
- `README.md` – Project overview

---

## How to Run
1. Clone the repository.
2. Extract `Data.zip`.
3. Open `Primetrade_Data_Analysis.ipynb`.
4. Run all cells to reproduce the analysis.

---

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
