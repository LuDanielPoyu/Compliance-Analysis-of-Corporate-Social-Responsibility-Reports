# Compliance-Analysis-of-Corporate-Social-Responsibility-Reports

**Role:** NLP/ML Engineer (Student Research Project)
**When:** July 2023 – June 2024 · **Original Repo:**[https://github.com/csrone-dev]

> **Note:** This repo uses **synthetic data** and simplified notebooks to demonstrate my contributions.  
> No proprietary data or configs are included.

# ASML-System-Integration-and-Software-Testing-Engineer

**Role:** System Integration & Software Testing Intern (Part-Time: 24 hrs/wk)  
**When:** Jan 2024 – Dec 2024 · **Location:** Taipei, Taiwan  

> **Disclaimer:** This portfolio uses sanitized descriptions and **synthetic examples only**. No proprietary code, data, screenshots, internal IDs, or configurations from ASML are included.

---

## Projects at a Glance

| Project | Problem | What I Built | Result | Stack |
|---|---|---|---|---|
| **P1. YieldStar Log Quality Assurance Automated Pipeline** | Noisy and multi-source logs slowed triage | Python validator packaged one-click tool with schema/regex checks, caching, retry | **Processing time ↓ ~90%** | **Python**, **Pandas** (text analytics), **Pydantic/JSON Schema** (validation), **Pytest/Hypothesis** (tests), **Tenacity** (retry), **Redis** (cache) |
| **P2. Robot Framework API Test Suites & CI Quality Gates** | Post-merge defects surfaced late | Robot Framework API tests and GitHub Actions blocking PRs; JUnit reports for inspection | **Post-merge defects ↓ ~80%** | **Robot Framework**, **GitHub Actions**, **JUnit XML**, **pytest/coverage**, **pre-commit**, **Docker** |
| **P3. React log Viewer with Anomaly Flags** | Slow handoff from ops to investigation | Web application with anomaly flags via threshold & timestamp checks | **Handoff-to-investigation time ↓ ~60%** | **React**, **TypeScript**, **React Query**, **Docker**, **REST API (Flask/FastAPI)** |
| **P4. PowerBI Ops Dashboards** | Limited visibility into yieldstar machine log's health | Power BI dashboards with daily refresh, health checks, runbooks | Faster daily reviews that support **internal and external** projects | **Power BI**, **DAX**, **Power Query (M)**, **Scheduled Refresh**, **REST/CSV connectors**, **SQL** |







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
