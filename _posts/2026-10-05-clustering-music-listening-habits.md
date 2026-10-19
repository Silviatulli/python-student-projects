---
title: "Clustering Music Listening Habits"
categories: advanced
authors: ['Student H']
summary: "Unsupervised learning on audio features to discover listener profiles, with a reproducible packaged codebase."
tags: ['clustering', 'PCA', 'packaging']
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
