Victor G. Souto — Statistics, Data Science & Software Engineering

Jundiaí, SP • Statistics | Probabilistic Modeling | Time Series | ML
Email: victorgsouto20@gmail.com
 • LinkedIn: in/victor-goncalves-souto
 • GitHub: @VictorGSoutoXP

Executive Summary

Statistician and software engineer designing end-to-end analytical solutions: from data acquisition and engineering to modeling, validation, and production deployment. Focus areas include:

Forecasting and inference with time series, structural models, and Bayesian methods;

Uncertainty quantification and rigorous performance evaluation (backtesting, calibration, hypothesis testing);

Scalable solutions integrated into pipelines and applications (including mobile) when required by the product.

Statistical & Modeling Focus
Time Series

Classical models: ARIMA/SARIMA (auto_arima & grid search), ETS/Holt–Winters, Theta, State-Space/UCM, SARIMAX (exogenous regressors), and VAR/VARMAX for multivariate settings.

Volatility: ARCH/GARCH/EGARCH for conditional variance dynamics.

Diagnostics: stationarity (ADF, KPSS), autocorrelation (ACF/PACF), Ljung–Box, regime shifts, heteroskedasticity.

Temporal validation: rolling-origin / expanding windows, one-step-ahead & multi-step, walk-forward evaluation.

Metrics: SMAPE, robust MAPE, WMAPE, MAE/RMSE, directional accuracy; information criteria AIC/BIC where applicable.

Typical transformation: log-price yt=log(pt) for variance stabilization and log-normal interval construction.

Bayesian Inference & Probabilistic Forecasting

Prophet (trend + seasonality; posterior and native intervals); emphasis on forecast intervals and calibration (reliability vs. sharpness).

Model combination (ensembles): weights driven by out-of-sample error and directional accuracy; trimmed ensembles to reduce tail risk.

Uncertainty quantification: propagate forecast volatility in log space; log-normal confidence intervals with empirical coverage checks.

Econometrics & Learning

Regression: GLM/GAM, fixed/random effects; cointegration (Johansen), VAR/VECM when appropriate.

Supervised ML for forecasting: lag features, rolling windows, gradient boosting (XGBoost/LightGBM).

Causality (when relevant): synthetic controls, difference-in-differences, and causal time-series designs.

Data Engineering & Software

Languages/stack: Python (NumPy, Pandas, SciPy, statsmodels, pmdarima, arch, Prophet), SQL, Power BI.

Pipelines: orchestration, data/model versioning, logging & monitoring (data drift, concept drift).

Applications: model integration into services/APIs and mobile apps when user experience is part of the product.

Selected Applied Experience

Operational/financial forecasting with exogenous drivers (market, on-chain, macro), scenario analysis, and stress testing.

Probabilistic forecasting systems with backtesting and interval coverage monitoring.

Executive dashboards showing model performance, decomposition, and explainability.

Practices & Standards

Honest backtesting: temporal splits without look-ahead.

Diagnostics before modeling: hypothesis tests, residual analysis, parameter stability.

Simplicity first: begin with interpretable baselines; add complexity where gains are demonstrated.

Documentation & reproducibility: declarative environments, controlled seeds, automated reporting.

Certifications

Microsoft Certified: Data Analyst Associate

Google Data Analytics Professional Certificate

AWS Certified Cloud Practitioner

Research & Current Interests

Nowcasting and high-frequency time series

Regime switching and structural break detection

Calibrated probabilistic forecasts (CRPS, PIT, coverage)

Model-to-product integration with business metrics and drift monitoring

Contact

Email: victorgsouto20@gmail.com

“The goal is not to guess the future, but to produce predictive, testable distributions that inform decision-making under uncertainty.”
