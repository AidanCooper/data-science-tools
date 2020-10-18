# Data Science Tools

Experiments and code samples for various tools related to data science workflows.

---

## Interpretable Machine Learning
| Tool | Experiments | Description |
| ----- | -------- | --------------------- |
| [RuleFit](https://github.com/christophM/rulefit) | [Example](notebooks/RuleFit.ipynb) | - A rules-based prediction algorithm.<br>- Supposedly, meets/exceeds the performance of Random Forest models, but retains the explainability of decision trees.|

## Databases
| Tool | Experiments | Description |
| ----- | -------- | --------------------- |
| [sqlite3](https://docs.python.org/3/library/sqlite3.html) | [Example](notebooks/sqlite3.ipynb) | - SQLite is a C library that provides a lightweight disk-based database that doesn’t require a separate server process and allows accessing the database using a nonstandard variant of the SQL query language.<br>- Part of the Python standard library.|

## Tools
| Tool | Experiments | Description |
| ----- | -------- | --------------------- |
| [nbstripout](https://github.com/kynan/nbstripout) |  | - Clean diffs whilst working with Jupyter notebooks.<br>- Personal preferred configuration after installing: edit the first line of `.\.git\info\attributes` to:<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"*.ipynb filter=nbstripout --keep-count --keep-output"|