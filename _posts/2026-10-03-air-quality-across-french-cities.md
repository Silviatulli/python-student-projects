---
title: "Air Quality Across French Cities"
categories: basic
authors: ['Student D', 'Student E']
summary: "Comparing pollution levels between cities and seasons using open government data."
tags: ['open data', 'groupby', 'seaborn']
image: /assets/img/placeholders/air-quality.jpg
image_credit: "Photo: Eltiempo10 / Wikimedia Commons, CC BY-SA 4.0"
image_credit_url: https://commons.wikimedia.org/wiki/File:Salt_Lake_City_smog_haze_skyline_01.jpg
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

*Placeholder text.* The main steps of the analysis — cleaning the data, handling missing values, and exploring it with summary statistics and plots.

```python
summary = df.groupby("category")["value"].mean()
summary.plot(kind="bar")
```

## Results

<div class="figure-placeholder">Figure will go here</div>

*Placeholder text.* The key findings, illustrated with one or two figures.

## Limitations and next steps

*Placeholder text.* What could be improved with more time or more data.
