---
title: <% tp.file.title %>
type: study-note
course: "" # e.g., "Calculus I" or "Philosophy of Language"
topic: "" # main topic covered
date: <% tp.date.now("YYYY-MM-DD") %>
tags: [study, <% tp.file.title %>]
difficulty: "" # e.g., beginner, intermediate, advanced
references: [] # optional list of books/papers
related: [] # links to related notes
---

# <% tp.file.title %>

> Main heading automatically filled with the note title.

---

## 🎯 Objectives

> Define the learning goals or what this note aims to clarify.

-
- ***

## 📘 Summary

> Concise overview of the concept, theorem, or reading.

Write a 3–5 sentence abstract here.

---

## 🧩 Core Concepts

> Bullet points of key definitions, formulas, or arguments.

- **Definition:**
- **Formula:**
- **Idea:**

You can use inline LaTeX for math:  
`$E = mc^2$` or

$$
\int_0^1 f(x)\,dx
$$

---

## 🧮 Derivations / Proofs

> Step-by-step logic or math work.

```latex
% Example
\begin{align}
a^2 + b^2 &= c^2 \\
\therefore c &= \sqrt{a^2 + b^2}
\end{align}
```

## 💡 Insights & Intuition

Write in your own words what this means and why it works.
Add analogies, visual interpretations, or “aha” moments.

## 🧠 Examples

Worked examples or sample problems.

### Example 1

1. Problem:
2. Solution steps:
3. Result:

### Example 2

...

---

## 🧰 Related Tools / Code

Relevant code snippets, algorithms, or tools (Python, Rust, etc.)

```python
# Example: Numerical integration
import numpy as np
f = lambda x: x**2
result = np.trapz([f(x) for x in np.linspace(0, 1, 100)], dx=0.01)
print(result)
```

## 🧭 Connections

Cross-link to related notes or larger frameworks.

- [[<% tp.file.cursor(1) %>]] # link to a related note
- [[Core Concepts Index]]

## 📚 References

Cite using your BibTeX keys if using the Citations plugin, or add manually.

- [@einstein1905]
- Book: Principia Mathematica, Newton

## 🧾 Review Questions

Optional — add comprehension or recall questions for spaced repetition.

1. lorem?
2. ipsum?

## ✅ Summary Table (Dataview)

Optional Dataview summary of all study notes in the same course.

```dataview
table topic, difficulty, date
from "Notes"
where course = this.course
sort date desc
```
