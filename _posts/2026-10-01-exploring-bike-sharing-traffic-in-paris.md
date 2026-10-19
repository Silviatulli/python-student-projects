---
title: "Exploring Bike-Sharing Traffic in Paris"
categories: basic
authors: ['Student A', 'Student B']
summary: "How does bike-sharing usage change with weather and time of day? A first exploration with pandas and matplotlib."
tags: ['pandas', 'matplotlib', 'time series']
image: /assets/img/placeholders/bike-sharing.jpg
image_credit: "Photo: Sharon Hahn Darlin / Wikimedia Commons, CC BY 2.0"
image_credit_url: https://commons.wikimedia.org/wiki/File:Velib%E2%80%99_M%C3%A9tropole,_Paris,_France.jpg
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
