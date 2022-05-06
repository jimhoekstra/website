---
layout: ../../components/BlogPostLayout.astro
title: Polynomial Regression
year: 2022
month: 5
day: 4
series: Machine Learning from Scratch
description: This is another test blog post.
---

<h1>{frontmatter.title}</h1>

<div class="text-dark text-opacity-50 mb-4">
    {frontmatter.day}-{frontmatter.month}-{frontmatter.year} | {frontmatter.series}
</div>

This is a second test blog post. We are using it to test how multiple blogs are
visualized on the blog overview pages, and whether the sorting of dates is 
happening correctly.

```python
def f(x):
    return x
```

Here we see some Python code.

<div>
    <img src="/imgs/figure1.png" class="mx-auto d-block">
</div>

And a figure with data points to which we would like to fit a polynomial curve.

<a href="/blog">Back</a>