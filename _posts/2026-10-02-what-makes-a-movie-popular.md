---
title: "What Makes a Movie Popular?"
categories: basic
authors: ['Student C']
summary: "Cleaning and exploring a movie ratings dataset to look for links between genre, budget and audience scores."
tags: ['pandas', 'data cleaning', 'visualisation']
image: /assets/img/placeholders/movies.jpg
image_credit: "Photo: Nathan from London, United Kingdom / Wikimedia Commons, CC BY-SA 2.0"
image_credit_url: https://commons.wikimedia.org/wiki/File:Gaumont_State_Cinema_Kilburn_2013-09-21_11.55.59_(by_Nathan).jpg
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
