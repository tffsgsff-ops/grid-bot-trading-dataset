# 🤖 Grid Bot Wars — Empirical Trading Benchmark Dataset

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Website](https://img.shields.io/badge/Website-gridbotwars.com-00eaff)](https://gridbotwars.com/)

Official research dataset tracking 50 automated algorithmic grid trading bots operating on Bybit across high-volatility cryptocurrency markets.

## 📊 Dataset Structure
- `data/season1_performance_matrix.json` & `.csv`: 31-day simulation baseline (50 bots).
- `data/season2_performance_matrix.json` & `.csv`: 31-day high-volatility futures battle (+914.8% top ROI).
- `data/season3_performance_matrix.json` & `.csv`: Live season checkpoints (SOL, ETH, BTC, SUI leaders).

## 🔬 Methodology
- Execution Frequency: Real-time orderbook micro-spread captures.
- Fee Structure: Bybit VIP 0 tiers (Maker 0.02% / Taker 0.055%).
- Spacing: 14-period ATR volatility expansion bands.

## 📜 Academic Citation
Please cite using the included `CITATION.cff` or:
```bibtex
@dataset{gridbotwars2026,
  author = {Grid Bot Wars Quantitative Lab},
  title = {Grid Bot Wars: High-Frequency Cryptocurrency Grid Trading Empirical Dataset},
  year = {2026},
  publisher = {GitHub},
  url = {https://gridbotwars.com/}
}
```
