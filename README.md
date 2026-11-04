# Hamilton Nascimento

Electrical engineer (UFAM) and PhD candidate in Mathematics (Unicamp). I work where mathematical modeling, statistics and machine learning meet: building models that are rigorous, explainable and tied to real decisions.

My main interests are data science and related areas where modeling and analytical thinking make a difference.

## What I work with

- **Machine learning:** classification, model calibration and evaluation, explainability (SHAP), scikit-learn, LightGBM, XGBoost, CatBoost
- **Statistics and mathematics:** statistical modeling, time series and volatility models (GARCH), hypothesis testing and bootstrap, mathematical modeling
- **Finance:** credit risk (probability of default, credit policy), market risk (volatility forecasting, Value-at-Risk)
- **Programming and data:** Python (pandas, NumPy, statsmodels, arch, Matplotlib), SQL, C, Jupyter, LaTeX
- **Hardware:** embedded systems, VHDL

## Featured projects

### [Credit Risk Modeling](https://github.com/hnascimento96/Credit-Risk-Modeling)

End-to-end probability of default model on 150,000 customers: data treatments driven by the EDA, five models compared, sigmoid calibration, a PD-based credit approval policy and a SHAP challenger analysis.

- Calibrated, explainable Logistic Regression with a test ROC-AUC of 0.857
- At a 10% PD threshold: 86% of applicants approved, portfolio default rate down from 6.7% to 2.9%
- Fixing data issues found in the EDA raised the model's AUC by 0.04

### [Equity Volatility Forecasting](https://github.com/hnascimento96/equity-volatility-forecasting) *(in progress)*

Comparison of four daily volatility models for PETR4 (Petrobras): 21-day rolling volatility, RiskMetrics EWMA, and GARCH(1,1) with normal and Student-t innovations. The design separates the value of estimated, mean-reverting dynamics from the value of a heavy-tailed distribution.

- Volatility is highly persistent (half-life of about 121 trading days) but reacts to single shocks far less than EWMA implies
- Normality of the residuals is rejected for every model, while a Student-t with about 4 degrees of freedom is not rejected by a parametric bootstrap Anderson–Darling test (p = 0.47)
- Next: out-of-sample evaluation with QLIKE and MSE losses, Diebold–Mariano tests and Value-at-Risk backtests

## Contact

[LinkedIn](https://www.linkedin.com/in/hamilton-nascimento-7b9973144) · hnascimento.mat@gmail.com
