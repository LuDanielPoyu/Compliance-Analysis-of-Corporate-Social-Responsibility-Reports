# Compliance-Analysis-of-Corporate-Social-Responsibility-Reports

**Role:** NLP/ML Engineer (Student Project) · **When:** 2024 · **Org Repo:** [link-to-org-repo]

> **Note:** This repo uses **synthetic data** and simplified notebooks to demonstrate my contributions.  
> No proprietary data or configs are included.

## Problem
CSR reports are long and inconsistent. Teams needed **auditable, definition-aware checks** against ESG indicators.

## What I built
- **Definition-aware retrieval:** keyword + BM25 + embedding search to pull candidate spans per indicator.
- **Evidence bundling:** rules + ML scoring to assemble context windows for each check.
- **Decision layer:** lightweight classifier with calibrated thresholds; source-cited outputs.
- **Evaluation:** labeled samples; precision/recall & calibration plots; error taxonomy.

## Results (on synthetic setup mirroring real patterns)
- Accuracy lifted from **~52% → ~72%** on indicator checks; improved citation quality and consistency.

## Stack
**Python**, **PyTorch/HF**, **BM25/FAISS**, **scikit-learn**, **pandas**, **spaCy**, **Mermaid**

## Repo map
