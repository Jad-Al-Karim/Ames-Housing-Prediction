# Ames Housing — House Price Prediction

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24%2B-orange.svg)](https://scikit-learn.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)


Short description
- Jupyter notebook and ML pipeline to predict sale prices on the Ames Housing dataset.

Project overview
- `Ames_Housing.ipynb`: end-to-end notebook that performs data loading, preprocessing (imputation, encoding, scaling, categorical embeddings), feature selection, model training (LinearRegression, ElasticNet, MLPRegressor, GradientBoostingRegressor), hyperparameter tuning with `GridSearchCV`, and evaluation.
- `AmesHousing.csv`: dataset used for training and evaluation.

Quick start

1. Create and activate a Python environment, then install dependencies:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

2. Open the notebook and run cells (recommended: use Jupyter Lab or VS Code notebook support).

Notes
- This repository does not include a license file (per project preference).
- The notebook logs preprocessing decisions and prints the top correlated features; the target variable is transformed with `log1p` during modeling.

Suggested GitHub description (one line)
- "Jupyter notebook and ML pipeline to predict Ames Housing sale prices."

Suggested topics/tags
- `machine-learning`, `regression`, `scikit-learn`, `jupyter-notebook`, `dataset`

If you'd like additional README sections (examples, results, model artifacts, or visual badges), tell me what to include and I'll add them.
