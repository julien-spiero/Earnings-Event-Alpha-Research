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

## Data Requirements

The project's master dataset is **not included in this repository** due to data access and licensing restrictions.

To reproduce the analysis, the master dataset must be **obtained independently through a valid WRDS account** and loaded into the project before running the notebook.

The research relies on proprietary financial datasets accessed through **Wharton Research Data Services (WRDS)**. Users are responsible for obtaining the appropriate WRDS access and ensuring compliance with the applicable data licensing terms.

Once obtained, the master dataset should be placed in the appropriate `data/` directory and loaded by the notebook.

> **Important:** The repository does not provide, redistribute, or grant access to the underlying WRDS data.

## Repository Structure

```text
├── README.md
├── Earnings_Event_Alpha.ipynb
├── data/
│   └── [WRDS master dataset — not included]
├── results/
└── .gitignore
```

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
