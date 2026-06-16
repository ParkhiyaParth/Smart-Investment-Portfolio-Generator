# Smart Investment Portfolio Generator

This is an academic machine learning project focused on financial data analysis, feature engineering, and portfolio-style simulation. It demonstrates how historical datasets can be cleaned, transformed, analyzed, and used inside an ML workflow.

> This project is for learning and portfolio demonstration only. It is not financial advice.

## What This Project Does

- Processes historical financial datasets.
- Creates useful analytical features.
- Applies machine learning concepts for classification or recommendation-style simulation.
- Demonstrates practical Python-based data analysis.

## Tech Stack

Python, Pandas, NumPy, Scikit-learn, XGBoost, FastAPI, yfinance, Machine Learning, Data Analysis.

## Setup

```bash
git clone https://github.com/ParkhiyaParth/Smart-Investment-Portfolio-Generator.git
cd Smart-Investment-Portfolio-Generator
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

If `requirements.txt` is missing, install common packages manually:

```bash
pip install pandas numpy scikit-learn xgboost fastapi uvicorn yfinance
```

## Run

```bash
python app.py
```

or for FastAPI:

```bash
uvicorn main:app --reload
```

## Author

Parth Parkhiya

GitHub: https://github.com/ParkhiyaParth
