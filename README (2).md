# 📊 Trader Sentiment Analysis — Bitcoin Fear & Greed vs Hyperliquid Traders

**By Aditya**

An end-to-end data science analysis exploring the relationship between Bitcoin market sentiment and trader performance using real Hyperliquid trading data.

---

## 🗂️ Datasets Used

| Dataset | Records | Source |
|---|---|---|
| Hyperliquid Historical Trades | 211,224 trades | Hyperliquid DEX |
| Bitcoin Fear & Greed Index | 2,644 days | Alternative.me |
| Date Range | May 2023 – May 2025 | — |

---

## 🔑 Key Findings

- **Fear = Best avg PnL** → $54.29/trade during Fear vs $34 in Neutral markets
- **Extreme Greed SELL dominance** → SELL trades yield $114.58 avg (11× more than BUY)
- **Weak FG correlation** → r = 0.037, raw sentiment alone doesn't predict PnL
- **Volume peaks in Fear** → $483M traded — traders most active when market panics
- **Trade size drops in Greed** → Smart money scales down 60% in Extreme Greed
- **Top coins** → @107, HYPE, SOL = 62% of all PnL ($6.37M of $10.3M)

---

## 📈 Visualizations

![Dashboard](primetrade_analysis.png)

10-chart dashboard covering:
1. Total PnL by Sentiment
2. Avg PnL per Trade
3. Win Rate by Sentiment
4. BUY vs SELL by Sentiment
5. Trading Volume by Sentiment
6. Top 8 Coins by PnL
7. Monthly PnL trends (18 months)
8. FG Index vs Daily PnL scatter
9. Top 6 Traders by PnL
10. Key Metrics Summary

---

## 🚀 Strategy Signals

| Signal | Action |
|---|---|
| FG Index < 30 (Fear) | Go LONG — avg PnL $54–67/trade |
| FG Index > 75 (Extreme Greed) | Go SHORT/SELL — avg $114/trade |
| Position sizing | Scale DOWN 60% in Greed zones |
| Focus coins | @107, HYPE, SOL for max alpha |

---

## 🛠️ Tools Used

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn`

---

## 📁 Files

| File | Description |
|---|---|
| `primetrade_analysis.png` | 10-chart visual dashboard |
| `primetrade_report.html` | Full written report with insights |
| `README.md` | This file |
