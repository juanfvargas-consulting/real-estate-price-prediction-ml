# Real Estate Valuation & Predictive Modeling Pipeline

This project explores automated real estate valuation using both traditional econometrics and modern machine learning ensembles. The analysis utilizes a dataset of over 19,000 properties to predict housing prices and evaluate key architectural and geographical pricing drivers.

### Key Highlights & Technical Stack:
* **Econometric Modeling:** Implemented Ordinary Least Squares (OLS) regressions via `statsmodels` to evaluate linear and quadratic price relationships.
* **Diagnostics:** Conducted Variance Inflation Factor (VIF) analysis to detect and mitigate multicollinearity among housing features.
* **Machine Learning Ensembles:** Built and tuned Decision Trees, Bagging Regressors, and Random Forest models to capture non-linear market interactions.
* **Classification Tiering:** Modeled high/low price tiers using Logistic Regression and evaluated predictive performance via ROC-AUC metrics.
* **Python Libraries:** Pandas, NumPy, Scikit-Learn, Statsmodels, Seaborn, Matplotlib.
