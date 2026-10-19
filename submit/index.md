---
layout: default
title: How to submit your project
---
<div class="wrap narrow page" markdown="1">

# How to submit your project

At the end of the course, each group publishes its final data science project as a blog post on this site. Here is how.

## 1. Prepare your post

Copy the template [`_templates/project-template.md`](https://github.com/Silviatulli/python-student-projects/blob/main/_templates/project-template.md) and rename it:

```
_posts/YYYY-MM-DD-short-project-title.md
```

For example: `_posts/2027-01-20-paris-bike-traffic.md`.

## 2. Fill in the header

At the top of the file, set:

| Field | What to write |
|---|---|
| `title` | Your project title |
| `categories` | `basic` or `advanced` — the course you followed |
| `authors` | List of group members |
| `summary` | One or two sentences shown on the project card |
| `tags` | A few keywords (e.g. `pandas`, `visualisation`, `regression`) |
| `repo` / `notebook` | Optional links to your code |

## 3. Write the post

Aim for a short, readable article (roughly 800–1500 words):

1. **Question** — what did you want to find out, and why?
2. **Data** — where does it come from, and what does it look like?
3. **Method** — how did you clean, explore and analyse it? Include short code snippets.
4. **Results** — your key figures and what they show.
5. **Limitations & next steps** — what you would do with more time.

Put images in `assets/img/your-project-name/` and reference them like this:

```markdown
![Caption]({{ '{{' }} '/assets/img/your-project-name/figure1.png' | relative_url {{ '}}' }})
```

## 4. Open a pull request

Fork this repository, add your post (and images), and open a pull request. Your instructor will review it and publish it.

</div>
