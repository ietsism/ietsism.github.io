---
layout: post
title: How to confuse a Python programmer
image: "/assets/images/posts/python/python.jpg"
headerImage: true
tag:
- Python
- confusing
- code
category: blog
author: ietsism
description: Counter-intuitive line of code that could confuse your fellow Python
  programmers
published: true
date: 2020-09-25 20:49 +0200
---
While browsing the internet, I came across the following line of Python code:

```python
True, True, True == (True, True, True)
```

Counter-intuitively, if you execute the statement, you will end up with:

```python
(True, True, False)
```

How is this possible I asked myself? (Yes I was a confused Python programmer myself at that point). Well, the answer is relatively simple: `==` does not do the unpacking for us. So, as a human you think that Python does something along the lines of `(True, True, True) == (True, True, True)` or `True, True, True == True, True, True`. However, Python actually interprets the line as follows:

```python
True, True, (True == (True, True, True))
```

This means that it first evaluates whether `(True == (True, True, True))`, which is `False`. Then it returns the rest of the statement as a tuple:[^1] `(True, True, False)`.

Another case that can be explained in the same way is `False is False is False`. Can you guess what the result is when you execute that statement? Hint: Python evaluates the statement as `(False is False) & (False is False)`, which results in `True`. Now that makes sense, right?


### References
[^1]: ["A tuple is a collection which is ordered and unchangeable. In Python tuples are written with round brackets."](https://www.w3schools.com/python/python_tuples.asp)