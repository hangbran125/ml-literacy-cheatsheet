[README.md](https://github.com/user-attachments/files/29942430/README.md)
# ML Literacy Cheat Sheet

A one-stop reference for machine-learning fundamentals, written from a **security
practitioner's angle** — every algorithm and metric is tied back to what it means when
the positive class is "attack." Built as the Week 1 foundation for moving into AI/LLM
security.

---

## What's covered

**[`ML_Literacy_Cheat_Sheet_Week_1.ipynb`](ML_Literacy_Cheat_Sheet_Week_1.ipynb)** —
four sections, each with an optional runnable demo cell:

1. **ML basics** — supervised vs. unsupervised, classification vs. regression, and the
   core workflow (raw data → preprocess → train/test split → train → evaluate).
2. **Algorithms** — a comparison table of Decision Tree, Random Forest, Logistic
   Regression (and more): what each is, its strengths and weaknesses, when to reach
   for it, and a concrete **security use case** (alert triage, malware/intrusion
   detection, fraud).
3. **Metrics** — a confusion matrix labelled with its **security meaning** (a false
   negative = a missed attack, the costly outcome), plus precision, recall, F1,
   accuracy, balanced accuracy, and ROC-AUC — including why plain accuracy is
   misleading on imbalanced security data.
4. **Principles & gotchas** — overfitting vs. underfitting, class imbalance and what to
   do about it, when feature scaling matters, and how to read a suspiciously perfect
   score (often a data-leakage tell).

The demo cells are self-contained — each trains a small model on Iris (or a synthetic
imbalanced set) so you can watch the concept run.

## Run the demos

```bash
pip install -r requirements.txt
jupyter notebook ML_Literacy_Cheat_Sheet_Week_1.ipynb
```

## Skills demonstrated

ML fundamentals · translating generic ML concepts into security terms · evaluation
metrics for imbalanced detection problems · clear technical writing / reference-building.

---

<sub>Week 1 of a structured AI-security learning program (ML foundations → LLM
security → red teaming). Part of a portfolio documenting that progression.</sub>
