---
title: "Predicting Housing Prices with Gradient Boosting"
categories: advanced
authors: ['Student F', 'Student G']
summary: "A full ML pipeline — feature engineering, cross-validation and model interpretation — on real estate transaction data."
tags: ['scikit-learn', 'regression', 'SHAP']
image: /assets/img/placeholders/housing.png
placeholder: true
---

## The question

*Placeholder text.* Here the authors introduce the question they set out to answer, why it matters, and what they expected to find.

## The data

*Placeholder text.* A short description of the dataset: where it comes from, its size, and what each row represents.

```python
import pandas as pd

df = pd.read_csv("data/dataset.csv")
print(df.shape)
df.head()
```

## What we did

*Placeholder text.* The main steps of the analysis — feature engineering, model selection, cross-validation and evaluation.

```python
from sklearn.model_selection import cross_val_score
scores = cross_val_score(model, X, y, cv=5)
print(scores.mean())
```

## Results

<div class="figure-placeholder">Figure will go here</div>

*Placeholder text.* The key findings, illustrated with one or two figures.

## Limitations and next steps

*Placeholder text.* What could be improved with more time or more data.
