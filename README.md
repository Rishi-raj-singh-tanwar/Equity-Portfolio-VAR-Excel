# Equity Value-at-Risk (VaR) Modelling

This project demonstrates the implementation of three key VaR methodologies for a portfolio of U.S. banking stocks (Goldman Sachs, Morgan Stanley, and JPMorgan Chase) using Microsoft Excel.

## Overview

- **Assets Modeled**: GS, MS, JPM
- **Data Source**: Yahoo Finance - Historical daily Adj. Close price
- **Portfolio Weights**: Equal-weighted (can be adjusted)
- **VaR Confidence Levels**: 99%, 95%, 90%
- **Holding Periods**: 1-day

## Methods Implemented

| Method               | Description                                                |
|----------------------|------------------------------------------------------------|
| Parametric VaR       | Based on mean-variance-covariance and normal distribution  |
| Historical VaR       | Non-parametric method using sorted historical returns      |
| Monte Carlo VaR      | Simulated returns using random sampling                    |

## Backtesting

- **Traffic Light Backtesting** based on Basel recommendations
- **Kupiec Test** to validate model accuracy via likelihood-ratio statistics

## File Contents

- `Equity_VAR_Modelling.xlsx` – All VaR models, simulations, and validations

## Skills Demonstrated

- Financial risk modeling
- Excel modeling & simulation
- Probability theory & backtesting
- Portfolio risk management concepts

## Future Work

- Python integration for scalable risk analytics
- Use GARCH models for volatility forecasting

---

Feel free to connect if you'd like to collaborate on quant/risk modeling projects!
