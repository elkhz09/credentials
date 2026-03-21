# Eleanor Koh — Data & Financial Analytics Portfolio

Targeting roles in **data analysis**, **financial modelling**, **quantitative research**, and **asset management / portfolio analytics**.

---

## Core Strengths

- Portfolio analytics: construction logic, drift/rebalance, P&L accounting, risk controls
- Quantitative methods: time-series econometrics, Granger causality, stationarity testing, classification
- Data engineering: API integration, SQLite schema design, ETL pipelines, reproducible notebooks
- Python for financial data analysis, automation, and system design
- Finance domain: CFA Level I, FDP — investment analysis, portfolio theory, financial data methods

---

## Featured Projects

### Standalone Repositories

#### [Portfolio OS](https://github.com/elkhz09/portfolio-os)
**Discretionary macro portfolio management system**

A human-in-the-loop paper trading system covering the full operational stack of a discretionary PM workflow. Built around a strict command interface, pre-trade risk engine, and full audit trail.

- Target weight setting, drift computation, rebalance order generation
- Pre-trade risk checks: cash availability, position limits, tradable allowlist, duplicate prevention
- FIFO realised P&L tracking across all trades
- Every order requires explicit `/confirm` — nothing executes automatically
- Streamlit dashboard with allocation breakdown and P&L charts; Telegram bot interface

`Python` `SQLAlchemy` `Pydantic` `Streamlit` `SQLite` `portfolio analytics` `risk controls` `P&L accounting`

---

#### [ETF Research & Portfolio Analytics](https://github.com/elkhz09/tipranks-etf-analytics)
**ETF holdings overlap and portfolio look-through tool**

Pulls ETF holdings data via API, stores it in a local SQLite database, and computes stock-level exposure across multi-ETF portfolios. Supports thematic sleeve research across Asia, semiconductors, AI, and US market beta.

- Portfolio look-through: converts ETF weights into estimated stock-level exposures
- Holdings overlap analysis: identifies concentration risk from repeated exposures across thematic and regional ETFs
- CLI tooling and reproducible notebook workflow

`API integration` `portfolio look-through` `holdings analysis` `pandas` `SQLite` `Python packaging`

---

### Analyses — [`elkhz09/analysis`](https://github.com/elkhz09/analysis)

#### [COE Price Dynamics — Singapore](https://github.com/elkhz09/analysis/tree/main/coe-price-dynamics)
**Time-series econometric analysis of auction-cleared prices**

Investigates whether stabilising Singapore's vehicle population stabilises COE premiums, using 20+ years of LTA / data.gov.sg data. Applies a structured research methodology: EDA → stationarity diagnostics → Granger causality testing → interpretation.

Key finding: population-level supply caps do not stabilise prices. Bids received and new registrations Granger-cause premium changes — demand pressure and auction dynamics dominate short-run price formation.

`time-series` `ADF stationarity` `Granger causality` `Statsmodels` `Python` `econometrics`

---

#### [Recipe Traffic Prediction](https://github.com/elkhz09/analysis/tree/main/datacamp-capstone)
**Binary classification for content optimisation (DataCamp capstone)**

Predicts high-traffic recipes for a digital food platform. Logistic Regression achieved 87% precision against an 80% business target. Demonstrates a complete data science workflow: EDA → feature engineering → model comparison → business recommendation.

`classification` `feature engineering` `scikit-learn` `business framing` `model selection`

---

## Certifications

| Credential | Issuer | Skills Demonstrated |
|---|---|---|
| CFA Level I | CFA Institute | Investment analysis, equity/fixed income/derivatives, portfolio management, quantitative methods |
| Financial Data Professional (FDP) | FDP Institute | Time-series analysis, regression diagnostics, statistical inference for financial data |
| Data Scientist Professional | DataCamp | End-to-end data science: EDA, statistical inference, supervised learning, model evaluation |
| GitHub Foundations | GitHub | Git workflows, version control, branching, collaboration |
| Python and Statistics for Financial Analysis | Coursera | Financial time-series, statistical methods, Python |
| Analyze Financial Data with Python | Codecademy | Financial data pipelines, visualisation |
| Finance Fundamentals Skill Track | DataCamp | Financial markets, instruments, data-driven analysis |

Full details and verification links in [certifications/](certifications/).

---

## Skills

| Area | Tools / Methods |
|---|---|
| Languages | Python, SQL |
| Analytics | Time-series, regression, classification, hypothesis testing, EDA |
| Finance | Portfolio construction, P&L, rebalance logic, ETF analytics, market microstructure |
| Tools | pandas, NumPy, Statsmodels, scikit-learn, SQLAlchemy, Streamlit, Jupyter |
| Dev | Git, modular packaging, unit tests, SQLite schema design |
