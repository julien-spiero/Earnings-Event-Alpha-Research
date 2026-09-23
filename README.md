# Earnings Event Alpha Research

A quantitative research project investigating **pre-earnings signals** to predict benchmark-adjusted stock price movements around earnings announcements.

## Overview

Built a machine learning pipeline across **2,000+ earnings events** using **59 features** combining market data, analyst revisions, options sentiment, and NLP signals.

The objective was to predict the **direction of benchmark-adjusted returns on the earnings announcement date (D=0)**.

## Methodology

* 2,000+ earnings events
* 59 engineered features
* NLP and analyst estimate revisions
* Put/Call ratios
* PCA dimensionality reduction
* Random Forest classification
* Out-of-sample validation
* Event-driven backtesting
* No look-ahead bias

## Results

* **75% out-of-sample classification accuracy**
* **71% strategy win rate**
* **+0.80% mean return per earnings event**

## Tech Stack

Python · Pandas · NumPy · Scikit-learn · NLP · PCA · Random Forest

## Repository Structure

```text
├── README.md
├── Earnings_Event_Alpha.ipynb
├── data/
├── results/
└── .gitignore
```

## Disclaimer

This project is for research and educational purposes only and does not constitute investment advice.
