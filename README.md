# Eleanor Koh

Index of my public work, and the credentials behind it. Targeting data and
product roles where the work involves building things that handle money or
operational state.

---

## Projects

**[Portfolio OS](https://github.com/elkhz09/portfolio-os)** — paper-trading
system for running a discretionary portfolio. Strict command parser, pre-trade
risk checks, append-only cash ledger, FIFO realised P&L, Telegram and Streamlit
interfaces. 181 tests. Nothing executes without explicit confirmation, and the
system never selects an investment.

**[ETF Research & Portfolio Analytics](https://github.com/elkhz09/tipranks-etf-analytics)**
— ETF holdings ingestion into SQLite, then look-through from ETF weights to
estimated stock-level exposure. Built to find out how much of a nine-ETF
allocation was the same handful of companies bought repeatedly.

**[COE Price Dynamics](https://github.com/elkhz09/analysis/tree/main/coe-price-dynamics)**
— time-series work on Singapore's vehicle quota auction. Population has been
flat since 2016, premiums have not. Granger causality puts the driver in bidding
activity rather than stock-level supply: the quota sets how many certificates
exist, competition sets what they cost.

**[Recipe Traffic Prediction](https://github.com/elkhz09/analysis/tree/main/datacamp-capstone)**
— classification under an asymmetric cost. Chose logistic regression at 0.87
precision over a gradient-boosted model with better F1, because the better F1
came with 0.74 precision and the brief set a floor of 0.80.

---

## Credentials

| Credential | Issuer | Verification |
|---|---|---|
| CFA Level I | CFA Institute | [basno](https://basno.com/lq0k1974) |
| Financial Data Professional | FDP Institute | [Credly](https://www.credly.com/badges/2784e228-b5be-4741-92fb-fa3b4239c696) |
| Data Scientist Professional | DataCamp | — |
| Python Data Associate | DataCamp | — |
| GitHub Foundations | GitHub | — |
| IBM Data Science Professional | Coursera / IBM | — |

Certificates and the coursework behind them are in
[`certifications/`](certifications/).

---

## Tools

Python, SQL, pandas, statsmodels, scikit-learn, SQLAlchemy, Pydantic, SQLite,
Streamlit, Jupyter, git.

---

## Licensing

The writing in this repository is mine. The certificates, course handouts and
supplied datasets under `certifications/` are issued or owned by the relevant
institutions and are included for reference only, not relicensed.
