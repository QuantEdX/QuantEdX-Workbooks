# QuantEdX Notebooks Catalog

This document provides a comprehensive catalog of all Jupyter notebooks referenced in the QuantEdX platform, organized by category and difficulty level.

**Last Updated:** November 30, 2025

---

## Summary

- **Total Notebooks Referenced:** 36
- **Currently Available Locally:** 2
- **Missing Notebooks:** 34
- **Categories:** 7

**Referenced In:**
- `/app/notebooks/page.jsx` - Main notebooks page
- `/app/learning/data/page.jsx` - Data Science Learning Pathway (filters by ML/data keywords)
- `/app/learning/quant/page.jsx` - Quantitative Finance Learning Pathway (filters by quant/trading keywords)

**Note:** All three pages use the same `RAW_NOTEBOOKS` array from `/app/notebooks/page.jsx`. The learning pathway pages filter notebooks based on relevant keywords for their respective domains.

---

## Categories Overview

### 1. Derivatives & Volatility (7 notebooks)

Covers option pricing, Greeks, volatility surfaces, hedging strategies, and variance derivatives.

#### Beginner
- **Options Vocabulary Workbook** (`options-vocabulary.ipynb`)
  - Introduce options terminology, payoff diagrams, and small quizzes before diving deeper
  - Tags: Options, Vocabulary, Payoffs
  - Status: ❌ Missing

#### Intermediate
- **Black-Scholes Greeks Playground** (`black-scholes-greeks.ipynb`)
  - Interactively compute option sensitivities while exploring volatility smiles and stress scenarios
  - Tags: Options, Greeks, Risk
  - Status: ❌ Missing

- **Event-Driven Option Analysis** (`option-event-analysis.ipynb`)
  - Study implied move pricing around earnings, macro prints, and cross-asset announcements
  - Tags: Options, Event Study, Earnings
  - Status: ❌ Missing

#### Advanced
- **Delta Hedging with Transaction Costs** (`delta-hedging.ipynb`)
  - Simulate rolling hedges under varying liquidity, slippage, and volatility regimes
  - Tags: Hedging, Transaction Costs, Simulation
  - Status: ❌ Missing

- **Volatility Surface Interpolation Toolkit** (`vol-surface.ipynb`)
  - Build, visualize, and stress-test volatility surfaces using SABR and spline techniques
  - Tags: Volatility, SABR, Visualization
  - Status: ❌ Missing

- **Variance Swap Pricing Demo** (`variance-swap-pricing.ipynb`)
  - Approximate fair strikes using realized variance estimators and replicating portfolios
  - Tags: Variance Swaps, Replication, Volatility
  - Status: ❌ Missing

---

### 2. Portfolio & Asset Allocation (6 notebooks)

Portfolio optimization, efficient frontier, factor analysis, cointegration, and factor timing strategies.

#### Intermediate
- **Mean-Variance Portfolio Optimizer** (`portfolio-optimization.ipynb`)
  - Run efficient frontier experiments, stress constraints, and compare Sharpe ratios across regimes
  - Tags: Portfolio, Optimization, PyPortfolioOpt
  - Status: ❌ Missing

- **Pairs Trading & Cointegration Lab** (`pairs-trading.ipynb`)
  - Test cointegration, calibrate hedge ratios, and run mean-reversion strategies with alerts
  - Tags: Stat Arb, Cointegration, Backtesting
  - Status: ❌ Missing

- **Factor Timing Dashboard** (`factor-timing.ipynb`)
  - Blend macro indicators and crossover rules to time Fama-French style factor tilts
  - Tags: Factors, Timing, Macro
  - Status: ❌ Missing

#### Advanced
- **Factor Backtesting Lab** (`factor-backtest.ipynb`)
  - Rank factors, decompose returns, and evaluate information coefficients with sample equities data
  - Tags: Alpha, Backtesting, Pandas
  - Status: ❌ Missing

- **Stochastic Control for Asset Allocation** (`stochastic-control.ipynb`)
  - Solve dynamic programming problems using Hamilton-Jacobi-Bellman formulations
  - Tags: Stochastic Control, Dynamic Programming, Allocation
  - Status: ❌ Missing

- **Qlib Alpha Workbench** (`qlib-alpha.ipynb`)
  - Prototype and backtest alpha factors with Microsoft Qlib datasets and pipeline APIs
  - Tags: Alpha, Pipeline, Qlib
  - Status: ❌ Missing

---

### 3. Risk & Stress Testing (6 notebooks)

Risk metrics, VaR, credit modeling, default prediction, climate risk, and quantile regression.

#### Beginner
- **Intro to Risk Metrics** (`risk-metrics-intro.ipynb`)
  - Walk through volatility, drawdown, and Sharpe ratio calculations using tidy helper functions
  - Tags: Risk, Metrics, Sharpe
  - Status: ❌ Missing

- **Loan Default Prediction with Gradient Boosting** (`loan-default.ipynb`)
  - Train, calibrate, and explain boosted credit models with SHAP insights
  - Tags: Credit, ML, Explainability
  - Status: ❌ Missing

#### Intermediate
- **Quantile Regression Risk Forecasts** (`quantile-risk.ipynb`)
  - Estimate VaR and Expected Shortfall with quantile regression and backtesting utilities
  - Tags: Risk, VaR, Quantile Regression
  - Status: ❌ Missing

- **Climate Scenario Risk Explorer** (`climate-risk.ipynb`)
  - Stress portfolios under NGFS pathways and measure sector exposures to climate risk
  - Tags: ESG, Scenario Analysis, Stress Testing
  - Status: ❌ Missing

#### Advanced
- **Credit Spread & Default Modeling** (`credit-spreads.ipynb`)
  - Estimate hazard rates, survival probabilities, and tranche exposure via Monte Carlo
  - Tags: Credit, Default, Risk
  - Status: ❌ Missing

---

### 4. Market Structure & Microstructure (2 notebooks)

Order flow analysis, liquidity metrics, market microstructure diagnostics.

#### Intermediate
- **Market Microstructure Diagnostics** (`market-microstructure.ipynb`)
  - Profile order book dynamics, estimate liquidity metrics, and detect toxic flow
  - Tags: Microstructure, Liquidity, Analytics
  - Status: ❌ Missing

#### Advanced
- **Machine Learning on Order Flow** (`ml-order-flow.ipynb`)
  - Apply tree-based models and embeddings to classify short-term direction from flow features
  - Tags: Machine Learning, Order Flow, PyTorch
  - Status: ❌ Missing

---

### 5. Machine Learning & Data (7 notebooks)

Alternative data, NLP sentiment, time series forecasting, feature engineering, and network analysis.

#### Beginner
- **Monte Carlo Scenario Simulator** (`monte-carlo-scenarios.ipynb`)
  - Model correlated paths, apply regime-dependent shocks, and visualize distribution shifts
  - Tags: Monte Carlo, Simulation, Visualization
  - Status: ❌ Missing

#### Intermediate
- **News Sentiment & Signal Extraction** (`news-sentiment.ipynb`)
  - Use NLP pipelines to convert news headlines into tradeable sentiment indicators
  - Tags: NLP, Sentiment, Signals
  - Status: ❌ Missing

- **Time Series Forecasting Toolkit** (`time-series-forecasting.ipynb`)
  - Apply ARIMA, Prophet, and LSTM architectures to forecast volatility and spreads
  - Tags: Time Series, Forecasting, Deep Learning
  - Status: ❌ Missing

#### Advanced
- **Alternative Data Feature Store** (`alt-data-feature-store.ipynb`)
  - Ingest satellite and payment datasets, engineer features, and evaluate predictive lift
  - Tags: Alternative Data, Feature Engineering, Pipelines
  - Status: ❌ Missing

- **FinTech Graph Network Analyzer** (`fintech-graph.ipynb`)
  - Explore payment network graphs, centrality metrics, and contagion across nodes
  - Tags: Graph Analytics, FinTech, Network
  - Status: ❌ Missing

---

### 6. Macro, ESG & Scenario (3 notebooks)

FX trading, interest rate curves, macro scenario analysis.

#### Intermediate
- **FX Carry Backtester** (`fx-carry.ipynb`)
  - Analyze carry opportunities, forward curves, and PnL attribution across currency baskets
  - Tags: FX, Carry, Backtesting
  - Status: ❌ Missing

- **Rates Term Structure Bootstrapping** (`rates-term-structure.ipynb`)
  - Bootstrap discount curves, forward rates, and scenario analysis for cross-currency swaps
  - Tags: Rates, Bootstrapping, Curve
  - Status: ❌ Missing

---

### 7. Digital Assets & Emerging Markets (1 notebook)

Cryptocurrency liquidity, AMM pools, digital asset analysis.

#### Intermediate
- **Digital Asset Liquidity Dashboard** (`crypto-liquidity.ipynb`)
  - Visualize AMM pools, order book depth, and cross-exchange spreads for crypto tokens
  - Tags: Digital Assets, Liquidity, Visualization
  - Status: ❌ Missing

---

## Beginner Level Notebooks (10 total)

### Python & Data Fundamentals
1. **Python Fundamentals for Finance** (`python-fundamentals.ipynb`) ❌
2. **Pandas Data Exploration Playground** (`pandas-playground.ipynb`) ❌
3. **API Data Ingest Practice** (`api-data-ingest.ipynb`) ❌
4. **Visualizing Distributions with Matplotlib** (`visualizing-distributions.ipynb`) ❌

### Finance Basics
5. **Return Calculations 101** (`returns-math.ipynb`) ❌
6. **Intro to Risk Metrics** (`risk-metrics-intro.ipynb`) ❌
7. **Time Value of Money Drills** (`time-value-money.ipynb`) ❌

### Trading & Strategy
8. **ETF Backtest Starter Kit** (`etf-backtest-starter.ipynb`) ❌
9. **Factor Screener Lite** (`factor-screener-lite.ipynb`) ❌

### Options & Derivatives
10. **Options Vocabulary Workbook** (`options-vocabulary.ipynb`) ❌

### Simulation & Risk
11. **Monte Carlo Scenario Simulator** (`monte-carlo-scenarios.ipynb`) ❌

### Credit
12. **Loan Default Prediction with Gradient Boosting** (`loan-default.ipynb`) ❌

---

## Intermediate Level Notebooks (14 total)

1. **Black-Scholes Greeks Playground** (`black-scholes-greeks.ipynb`) ❌
2. **Mean-Variance Portfolio Optimizer** (`portfolio-optimization.ipynb`) ❌
3. **FX Carry Backtester** (`fx-carry.ipynb`) ❌
4. **Rates Term Structure Bootstrapping** (`rates-term-structure.ipynb`) ❌
5. **Market Microstructure Diagnostics** (`market-microstructure.ipynb`) ❌
6. **Event-Driven Option Analysis** (`option-event-analysis.ipynb`) ❌
7. **Quantile Regression Risk Forecasts** (`quantile-risk.ipynb`) ❌
8. **Pairs Trading & Cointegration Lab** (`pairs-trading.ipynb`) ❌
9. **News Sentiment & Signal Extraction** (`news-sentiment.ipynb`) ❌
10. **Digital Asset Liquidity Dashboard** (`crypto-liquidity.ipynb`) ❌
11. **Factor Timing Dashboard** (`factor-timing.ipynb`) ❌
12. **Climate Scenario Risk Explorer** (`climate-risk.ipynb`) ❌
13. **Time Series Forecasting Toolkit** (`time-series-forecasting.ipynb`) ❌

---

## Advanced Level Notebooks (10 total)

1. **Factor Backtesting Lab** (`factor-backtest.ipynb`) ❌
2. **Delta Hedging with Transaction Costs** (`delta-hedging.ipynb`) ❌
3. **Volatility Surface Interpolation Toolkit** (`vol-surface.ipynb`) ❌
4. **Credit Spread & Default Modeling** (`credit-spreads.ipynb`) ❌
5. **Variance Swap Pricing Demo** (`variance-swap-pricing.ipynb`) ❌
6. **Machine Learning on Order Flow** (`ml-order-flow.ipynb`) ❌
7. **Alternative Data Feature Store** (`alt-data-feature-store.ipynb`) ❌
8. **Stochastic Control for Asset Allocation** (`stochastic-control.ipynb`) ❌
9. **Qlib Alpha Workbench** (`qlib-alpha.ipynb`) ❌
10. **FinTech Graph Network Analyzer** (`fintech-graph.ipynb`) ❌

---

## Currently Available Notebooks (2 total)

### In `content/notebooks/` directory:

1. ✅ **Option Greeks Complete** (`option_greeks_complete.ipynb`)
   - Category: Derivatives & Volatility
   - Level: Not specified in catalog
   - Size: 27KB
   - Status: Available locally

2. ✅ **Fundamentals of Quantitative Finance** (`fundamentals_of_quantitative_finance.ipynb`)
   - Category: Multi-category (covers fundamentals)
   - Level: Beginner to Intermediate
   - Size: 28KB
   - Status: Available locally (newly created)

---

## Notebooks by Topic Tags

### Python/Programming
- python-fundamentals.ipynb
- pandas-playground.ipynb
- api-data-ingest.ipynb

### Options & Derivatives
- options-vocabulary.ipynb
- black-scholes-greeks.ipynb
- option-event-analysis.ipynb
- delta-hedging.ipynb
- variance-swap-pricing.ipynb

### Volatility
- vol-surface.ipynb
- black-scholes-greeks.ipynb
- variance-swap-pricing.ipynb

### Portfolio Management
- portfolio-optimization.ipynb
- factor-backtest.ipynb
- factor-screener-lite.ipynb
- factor-timing.ipynb

### Risk Management
- risk-metrics-intro.ipynb
- quantile-risk.ipynb
- credit-spreads.ipynb
- climate-risk.ipynb

### Trading Strategies
- etf-backtest-starter.ipynb
- pairs-trading.ipynb
- fx-carry.ipynb
- market-microstructure.ipynb

### Machine Learning
- ml-order-flow.ipynb
- loan-default.ipynb
- news-sentiment.ipynb
- time-series-forecasting.ipynb
- alt-data-feature-store.ipynb

### Visualization
- visualizing-distributions.ipynb
- vol-surface.ipynb
- monte-carlo-scenarios.ipynb
- crypto-liquidity.ipynb

### Fixed Income & Rates
- rates-term-structure.ipynb
- credit-spreads.ipynb
- time-value-money.ipynb

### Digital Assets
- crypto-liquidity.ipynb

### Network Analysis
- fintech-graph.ipynb

---

## Repository Links

All notebooks are hosted at: `https://colab.research.google.com/github/quantedx/notebooks/blob/main/[filename].ipynb`

**Note:** The actual GitHub repository `quantedx/notebooks` appears to be the primary source for these notebooks, not the local `content/notebooks/` directory.

---

## Implementation Status

| Status | Count | Percentage |
|--------|-------|------------|
| ❌ Missing | 34 | 94.4% |
| ✅ Available | 2 | 5.6% |
| **Total** | **36** | **100%** |

---

## Learning Pathway Filtering

### Data Science Learning Pathway
**Filter Keywords:** machine learning, ml, data, analytics, python, pandas, feature, forecast, deep learning, neural, nlp, sentiment, time series

**Notebooks Included (by stage):**
- **Stage 1 - Foundations (Beginner):**
  - Python Fundamentals for Finance
  - Pandas Data Exploration Playground
  - API Data Ingest Practice

- **Stage 2 - Intermediate Skills (Intermediate):**
  - News Sentiment & Signal Extraction
  - Time Series Forecasting Toolkit
  - (Other intermediate ML/data notebooks)

- **Stage 3 - Advanced Concepts (Advanced):**
  - Machine Learning on Order Flow
  - Alternative Data Feature Store
  - FinTech Graph Network Analyzer
  - (Other advanced ML/data notebooks)

### Quantitative Finance Learning Pathway
**Filter Keywords:** quant, trading, portfolio, risk, option, derivative, volatility, alpha, factor, stat arb, backtest, hedge, market

**Notebooks Included (by stage):**
- **Stage 1 - Foundations (Beginner):**
  - ETF Backtest Starter Kit
  - Factor Screener Lite
  - Return Calculations 101

- **Stage 2 - Intermediate Skills (Intermediate):**
  - Black-Scholes Greeks Playground
  - Mean-Variance Portfolio Optimizer
  - FX Carry Backtester
  - Market Microstructure Diagnostics

- **Stage 3 - Advanced Concepts (Advanced):**
  - Factor Backtesting Lab
  - Delta Hedging with Transaction Costs
  - Volatility Surface Interpolation Toolkit
  - Credit Spread & Default Modeling

---

## Recommendations

1. **Create Missing Notebooks**: Prioritize creating notebooks based on:
   - Beginner level first (highest learning impact)
   - Most popular categories (Derivatives, Portfolio, Risk)
   - Dependencies (Python fundamentals before advanced topics)

2. **Suggested Creation Order**:
   - Phase 1: Python & Data basics (4 notebooks)
   - Phase 2: Finance fundamentals (3 notebooks)
   - Phase 3: Core quant topics (Options, Portfolio, Risk - 10 notebooks)
   - Phase 4: Advanced topics (19 notebooks)

3. **Repository Organization**: Consider syncing local notebooks with the GitHub repository mentioned in the URLs.

---

## Notes

- All notebooks in `app/notebooks/page.jsx` are marked as `comingSoon: true` by default
- Advanced level notebooks are locked (require upgrade to access)
- Each notebook includes Colab launch URL and downloadable .ipynb format
- The platform supports pagination (9 notebooks per page)
