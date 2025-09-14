# Bioinformatics – Prokaryotic and eukaryotic promoters Recognition and Prediction

This repository contains a single Jupyter notebook for **promoter recognition and prediction**. The work focuses on how to represent nucleotide sequences, build baseline and classical machine‑learning models, and evaluate performance with clear, reproducible metrics.

---

## What this notebook does
- Loads promoter / non‑promoter sequences (prokaryotic and/or eukaryotic).
- Performs basic quality checks and class distribution inspection.
- Encodes sequences for ML:
  - One‑hot (A,C,G,T)
  - k‑mer counts / TF‑IDF‑style features
  - (Optional) position‑aware features or motif windows
- Creates reproducible train/validation/test splits (stratified).
- Trains baseline and classical models (e.g., logistic regression, SVM, random forest, Naive Bayes).
- Evaluates with accuracy, precision, recall, F1, ROC‑AUC, and confusion matrices.
- Runs simple error analysis to inspect common failure cases and length/GC‑content effects.
- Summarizes takeaways and limitations.

---

## Learning outcomes
- Understand the **trade‑offs of sequence encodings** (one‑hot vs k‑mer).
- Practice building **reproducible ML pipelines** for biological sequence data.
- Read metrics correctly under potential **class imbalance** (why F1/ROC‑AUC matter).
- Interpret **confusion matrices** and common error patterns.
- Identify **next steps** (feature engineering, motif discovery, deep models).

---

## Repository layout
```
.
├── Bioinfomatics_1.ipynb      # main notebook
└── README.md
```

---
