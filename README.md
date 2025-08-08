# Statistical Methods in Finance – Portfolio Analysis Project
This repository contains the code, data, and results for Group 31’s Statistical Methods in Finance final project at Columbia University (Spring 2023). The project investigates portfolio optimization, risk management, and dependency modeling for a selection of 15 publicly traded stocks and the S&P 500 index.

## Project Overview
We analyzed historical monthly return data for 15 selected stocks to:

- Assess descriptive statistics, normality, and stationarity.

- Construct and evaluate Minimum Variance and Tangency Portfolios.

- Calculate Value-at-Risk (VaR) and Expected Shortfall (ES).

- Perform Principal Component Analysis (PCA) for dimensionality reduction.

- Model joint dependencies using copulas.

The work combines time series analysis, Markowitz portfolio theory, risk metrics, and multivariate modeling to gain insights into portfolio construction and asset risk.

## Key Findings
- Return Distributions: Most assets and the S&P 500 are approximately normally distributed with some stationarity.

- Tangency Portfolio:

  - Expected return: ~17.43%

  - Standard deviation: ~30.87%

  - Sharpe ratio: ~0.42

- Minimum Variance Portfolio (MVP): Lower VaR than most individual assets, with KO holding the largest weight.

- Risk Metrics:

  - Highest VaR: TSLA ($84,715.87)

  - Lowest VaR: KO ($26,945.52)

  - Risk levels significantly reduced when combining the tangency portfolio with risk-free assets.

- PCA: First four principal components explain the majority of return variance.

- Copula Modeling: Normal copula provided the best fit for joint distribution.

## Repository Structure
```

├── data/              # Raw and processed stock return data
├── src/               # Analysis scripts (portfolio construction, VaR/ES, PCA, copulas)
├── results/           # Output tables, plots, and model results
├── report/            # Final project report (PDF)
└── README.md          # Project description
```

## Methods Used
- Statistical Tests: Augmented Dickey-Fuller for stationarity, normality checks

- Portfolio Optimization: Markowitz mean-variance framework, no-short-sales constraint, tangency portfolio construction

- Risk Estimation: Parametric and nonparametric VaR & ES

- Multivariate Analysis: PCA, correlation heatmaps

- Dependency Modeling: Gaussian, Frank, Clayton, Gumbel, Joe copulas with AIC comparison

## Visualizations
The analysis includes:

- Efficient frontier plots

- Equity curves

- Correlation heatmaps

- PCA biplots & scree plots

- VaR/ES comparison charts

## Authors
- Andre Liu (azl2113)

- Lia Cho (lc3683)

## Course
Statistical Methods in Finance – Department of Statistics, Columbia University, Spring 2023

📅 Course
Statistical Methods in Finance – Department of Statistics, Columbia University, Spring 2023.
