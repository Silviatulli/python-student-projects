---
title: "Your Project Title"
categories: basic          # or: advanced
authors: ["First Student", "Second Student"]
summary: "One or two sentences describing your project — shown on the project card."
tags: [pandas, visualisation]
repo: https://github.com/your-username/your-project      # optional
notebook:                                                # optional link to a notebook
---

## The question

What did you want to find out, and why is it interesting?

## The data

Where does the data come from? How many rows/columns? What does one row represent?

```python
import pandas as pd
df = pd.read_csv("data.csv")
df.head()
```

## What we did

Describe cleaning, exploration and analysis steps. Keep code snippets short — link to the repo for the full code.

## Results

![Describe the figure]({{ '/assets/img/your-project-name/figure1.png' | relative_url }})

What does the figure show? What is the main take-away?

## Limitations and next steps

What would you improve with more time or more data?
