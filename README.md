# Crypto Volatility Modeling: BTC, ETH, and SOL

## Executive Summary
This project investigates volatility persistence in major cryptocurrencies  
(Bitcoin, Ethereum, and Solana) compared to a benchmark equity index (S&P500).  
Using GARCH-family models on daily returns from 2018–2025, I estimate  
conditional volatility, half-lives of volatility shocks, and out-of-sample  
forecast performance.  

Key result: **BTC volatility shocks last ~9 days, ETH ~7 days, vs. OMXS30 ~3 days.**  
This suggests crypto markets exhibit far stronger volatility clustering.  

## Methodology
- Data: Daily close prices from Yahoo Finance (Jan 2018 – Sep 2025).  
- Models: GARCH(1,1), EGARCH, GJR-GARCH.  
- Evaluation: Persistence (α+β), half-life of volatility,  
  out-of-sample 1-step forecast accuracy (QLIKE loss).  

## Main Findings
- BTC: Persistence = 0.94, Half-life ≈ 9 days.  
- ETH: Persistence = 0.92, Half-life ≈ 7 days.  
- SOL: Persistence = 0.88, Half-life ≈ 5 days.  
- OMXS30: Persistence = 0.76, Half-life ≈ 3 days.  
- GARCH forecasts outperform naïve volatility proxy in all cases.  

## Deliverables
- Report: [`report/final.pdf`](report/final.pdf)  
- Figures: [`outputs/figures/`](outputs/figures/)  
- Code: see `/notebooks`  

---
# crypto-volatility-modeling
