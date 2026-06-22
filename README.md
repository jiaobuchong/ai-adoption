# From Pilot to Payoff — IS630 Group Project

A global study of AI adoption maturity, business value, and workforce impact.
The analysis (proposal Sections 2–5) is split into 7 self-contained notebook modules.

## Module order

| # | Notebook | Content |
|---|----------|---------|
| 01 | `01_setup_and_data_prep.ipynb` | Problem & objectives (S2); data sources, quality checks, data dictionary, feature engineering & standardisation (S3) |
| 02 | `02_Q1_global_eda.ipynb` | Q1 — Global EDA and adoption patterns (S4.1) |
| 03 | `03_Q2_country_readiness.ipynb` | Q2 — Country-level digital readiness: correlation, VIF, PCA, OLS (S4.2) |
| 04 | `04_Q3_firm_level_drivers.ipynb` | Q3 — Firm-level drivers of advanced adoption (capability / investment / governance blocks): VIF multicollinearity check, standardised nested logistic regression with model comparison (pseudo-R2, AIC/BIC), standardised odds ratios (S4.3) |
| 05 | `05_Q4_business_payoff.ipynb` | Q4 — Business payoff & digital-maturity moderation: group tests, OLS, interaction (S4.4) |
| 06 | `06_Q5_workforce_and_bayesian.ipynb` | Q5 — Workforce outcomes & Beta-Binomial Bayesian inference (S4.5) |
| 07 | `07_conclusion_and_summary.ipynb` | Conclusions, recommendations, limitations, future work & evidence table (S5) |

Suggested reading order is 01 → 07.

## Running the notebooks

- Each module is **self-contained**: it re-runs the shared setup and data-prep block at the top, so notebooks can be run **independently, in any order**.
- Keep these data files in the same folder as the notebooks: `ai_company_adoption.csv`, `country_ai_index.csv`, `ai_industry_summary.csv`.
- Figures are written to `figures/`.
- Requirements: `pandas`, `numpy`, `scipy`, `statsmodels`, `scikit-learn`, `matplotlib`, `seaborn`.

The original combined notebook (`IS630_Analysis_Sections_2to_5_FIXED_v2.ipynb`) is kept for reference.
