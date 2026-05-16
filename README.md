# Income Prediction

A machine learning project that predicts whether an individual's annual income exceeds **$50K** based on demographic and employment features — a classic binary classification problem using the [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult).

## Features

- Complete ML pipeline: data loading → preprocessing → model training → evaluation
- Handles missing values, categorical encoding, and feature scaling
- Trains and compares multiple classifiers
- Visualises feature importance and model metrics

## Prerequisites

```bash
pip install -r requirements.txt
```

## Usage

```bash
jupyter notebook income.ipynb
```

Run all cells top to bottom. The notebook covers:
1. **EDA** — exploratory data analysis and visualisations
2. **Preprocessing** — handle nulls, encode categoricals, scale numerics
3. **Modelling** — Logistic Regression, Random Forest, etc.
4. **Evaluation** — accuracy, confusion matrix, classification report

## Dataset Features

| Feature | Type |
|---------|------|
| Age | Numeric |
| Workclass | Categorical |
| Education | Categorical |
| Occupation | Categorical |
| Hours per week | Numeric |
| Capital gain/loss | Numeric |
| **Income (target)** | Binary: ≤50K / >50K |
