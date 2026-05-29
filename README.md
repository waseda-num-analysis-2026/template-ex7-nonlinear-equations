# Exercise 7 — Nonlinear Equations (Fixed-Point Iteration and Newton)

Numerical Analysis 2026 / Lectures 7--8 assignment bundle.

This repository contains **Ex 7.0**, **Ex 7.1**, and **Ex 7.2** (all **Individual Work**).

---

## Files

| File | Topic |
|---|---|
| `nonlinear-equations-handout.qmd` | **Ex 7.0** — your edited copy of the shared Lectures 7--8 handout (≥ 3 Q&A blocks, Lecture 7 scope) |
| `ex7-1.qmd` | Fixed-point iteration for $f(x)=x^3-3x-1=0$ |
| `ex7-2.qmd` | Compare Newton, simplified Newton, and bisection for $f(x)=x-\cos x=0$ |
| `requirements.txt` | Python packages used in the exercises |

For Ex 7.0, copy
[`070/nonlinear-equations-handout.qmd`](https://github.com/waseda-num-analysis-2026/materials/blob/main/070/nonlinear-equations-handout.qmd)
from the `materials` repository into the root of this repository, then add
Q&A blocks following
[`AI_TUTOR.md`](https://github.com/waseda-num-analysis-2026/materials/blob/main/AI_TUTOR.md).
Focus on the Lecture 7 part (fixed-point iteration and one-dimensional Newton's method).

---

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Then select the `.venv` interpreter in VS Code / Cursor.

---

## Render

```bash
quarto render ex7-1.qmd
quarto render ex7-2.qmd
```

**IMPORTANT:** This creates `ex7-1.html`, `ex7-2.html`, and the corresponding
`ex7-*_files/` directories.

---

## Submission

```bash
git add nonlinear-equations-handout.qmd ex7-1.qmd ex7-2.qmd
git add ex7-1.html ex7-2.html ex7-1_files ex7-2_files
git commit -m "Submit Ex 7"
git push
```

You may push as many times as you like before the deadline; the **last
commit before the deadline** will be graded.

**IMPORTANT:** After pushing, open your repository on GitHub and check that
the rendered HTML files are visible in the browser.

**Deadline (JST):** June 4 (Thu), 23:59 JST.

---

## Need help?

- Mattermost: <https://class.s-top.dev/numerical-analysis-2026/channels/question>
- Materials repo: <https://github.com/waseda-num-analysis-2026/materials>
- Lecture 7 slides: <https://waseda-num-analysis-2026.github.io/materials/070/7th.html>
- Shared handout: <https://waseda-num-analysis-2026.github.io/materials/070/nonlinear-equations-handout.html>
