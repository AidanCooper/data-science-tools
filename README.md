# Data Science Tools

Experiments and code samples for various tools related to data science workflows.

---
## Bayesian
| Tool | Experiments | Description |
| ----- | -------- | --------------------- |
| [skopt.BayesSearchCV](https://scikit-optimize.github.io/stable/modules/generated/skopt.BayesSearchCV.html) | - [Example](notebooks/BayesSearchCV-RF.ipynb) - RandomForest with comparison versus GridSearchCV and RandomizedSearchCV.<br>- [Example](notebooks/BayesSearchCV-RF-extensive_search_v2.ipynb) - RandomForest with extensive search.<br>- [Example](notebooks/BayesSearchCV-LGBM.ipynb) - LightGBM with comparison versus GridSearchCV and RandomizedSearchCV.<br>- [Example](notebooks/BayesSearchCV-LGBM-extensive_search.ipynb) - LightGBM with extensive search. | - Bayesian optimization over hyper parameters.<br>- A drop-in replacement for scikit-learn's GridSearchCV and RandomizedSearchCV.<br>- Part of [scikit-optimize](https://scikit-optimize.github.io/stable/index.html) ("skopt").|

## Databases
| Tool | Experiments | Description |
| ----- | -------- | --------------------- |
| [sqlite3](https://docs.python.org/3/library/sqlite3.html) | - [Example](notebooks/sqlite3.ipynb) | - SQLite is a C library that provides a lightweight disk-based database that doesn’t require a separate server process and allows accessing the database using a nonstandard variant of the SQL query language.<br>- Part of the Python standard library.|

## Interpretable Machine Learning
| Tool | Experiments | Description |
| ----- | -------- | --------------------- |
| [RuleFit](https://github.com/christophM/rulefit) | - [Example](notebooks/RuleFit.ipynb) | - A rules-based prediction algorithm.<br>- Supposedly, meets/exceeds the performance of Random Forest models, but retains the explainability of decision trees.|
| [SkopeRules](https://github.com/scikit-learn-contrib/skope-rules) | - [Example](notebooks/SkopeRules.ipynb) | - Alternative implementation of RuleFit (above).|
| [ALEPython](https://github.com/blent-ai/ALEPython) | - [Example](notebooks/ALEPython.ipynb) | - Accumulated Local Effects (ALE) plots describe how features influence the prediction of a machine learning model on average.<br>- ALE plots are a faster and unbiased alternative to partial dependence plots (PDPs).|

## Statistics
| Tool | Experiments | Description |
| ----- | -------- | --------------------- |
| [Frequentist Inference](https://en.wikipedia.org/wiki/Frequentist_inference) | - [Example](notebooks/frequentist_inference.ipynb) | - Simple examples of Confidence Intervals, Hypothesis Testing, and P-values. |
| [Linear Regression](https://www.statsmodels.org/stable/generated/statsmodels.formula.api.ols.html) | - [Example](notebooks/linear_regression.ipynb) | - Simple Linear Regression and Multivariate Linear Regression using `statsmodels.formula.api.ols`. |

## Tools
| Tool | Experiments | Description |
| ----- | -------- | --------------------- |
| [nbstripout](https://github.com/kynan/nbstripout) |  | - Clean diffs whilst working with Jupyter notebooks.<br>- Personal preferred configuration after installing: edit the first line of `./.git/info/attributes` to:<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"*.ipynb filter=nbstripout --keep-count --keep-output"|
