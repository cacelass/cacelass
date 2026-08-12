# Alex | ML Engineer — Banking & Finance Focus

I build production-ready machine learning systems for the financial domain — credit, fraud, AML and
investment analysis — from raw data to deployed models, designed to be reproducible, testable and
operational in real environments.

Most ML projects fail outside the notebook. I focus on the production constraints that make a system
defensible in front of a reviewer: data quality, leakage prevention, calibration, honest evaluation,
and system reliability.

I'm passionate about data — inside and outside work. I love learning, taking on challenges and getting
better with every project. My professional aspiration is to build decision systems that real
institutions trust, and to keep growing as an ML engineer along the way.

Background in systems administration (ASIR). I design ML systems with infrastructure, failure modes and
performance in mind before model complexity.

---

## What I deliver

- End-to-end ML pipelines (ingestion → validation → feature engineering → training → evaluation → inference)
- Fraud and AML detection with imbalance-first evaluation (precision-recall, not accuracy)
- Credit and propensity models with calibrated probabilities and decoupled business thresholds
- Time-series models with temporal validation, out-of-sample backtest and cost awareness
- Reproducible environments with versioned data and locked dependencies (`uv`, Docker)
- Drift monitoring for models in production (PSI)
- ML systems decoupled from business decision logic

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-764ABC?style=flat&logo=lightgbm&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-E0234E?style=flat&logo=xgboost&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat&logo=polars&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)

**Certified:** Microsoft Azure Data Fundamentals · Power BI (DAX)
[Credly](https://www.credly.com/users/alejandro-cancelas-chapela/badges#credly) ·
[LinkedIn](https://www.linkedin.com/in/cacelas/)

---

## Featured Projects

### [dskit](https://github.com/cacelass/dskit) — Reproducible ML scaffold with an AI harness

Production-grade copier template that starts ML projects organised, reproducible and production-ready.
Ships an AI harness with an entry gate, a verifiable backlog and a definition of "done" enforced in code.

**What it enforces**
- Strict project structure and dependency locking with `uv`
- `harness finish` refuses to close a feature unless the gate passes with real command evidence
- 4 ML profiles, 6 NN architectures, Sphinx docs by default
- Two agent layers: reasoning agents + 30 deterministic Python agents

### [ClimaSafe](https://github.com/ANFAIA/ClimaSafe) — Early-warning system for heat/cold risk

Predicts thermal mortality risk per Spanish province and day (XGBoost + LSTM ensemble) with conformal
prediction, km² risk maps, SHAP explainability and a Telegram bot. Built on ERA5 + MoMo data.
Generated from the dskit template. Part of the ANFAIA Summer Grants 2026.

**Real numbers** — Rec_riesgo (calibrated): XGBoost 0.668 (heat), LSTM 0.737 (heat) / 0.708 (cold).

### [fraud-shield](https://github.com/cacelass/fraud-shield) — Fraud detection for fintech constraints

End-to-end fraud detection on PaySim (~6.3M transactions, ~0.1% fraud). LightGBM with
`class_weight='balanced'`, precision-recall as the primary lens, MLflow tracked.

**Real numbers** — ROC-AUC 0.998 with fraud-class P/R/F1 ≈ 0.84/0.77/0.80 at the tuned threshold.

### [credit-risk-classifier](https://github.com/cacelass/credit-risk-classifier) — Retail banking propensity

Propensity model on UCI Bank Marketing to prioritise who to call in a campaign. Leakage-free
preprocessing (transformers fitted on train only) and persisted, reproducible metrics.

**Real numbers** — ROC-AUC 0.948, PR-AUC 0.651, recall 0.92 on the positive class.

### [Stock-Market-Prediction](https://github.com/cacelass/Stock-Market-Prediction) — Time series under real constraints

Directional movement prediction with walk-forward validation, out-of-sample backtest with costs,
conformal prediction and drift monitoring. Honest about where it fails: after costs it does not beat
buy & hold — and it documents exactly why.

### [MeshHarmes](https://github.com/cacelass/MeshHarmes) — Agent harness in code

24 Python agents (stdlib-only), a permission gate for irreversible actions, and a verifiable backlog.
Provider-agnostic: any coding agent that can run shell commands can use it.

---

## In development

A **portfolio manager** system to decide when to reinvest and when to withdraw — built on the
evaluation rigour and backtest discipline of Stock-Market-Prediction.

---

## Positioning

I design ML systems that remain stable under real-world constraints: shifting data distributions,
imperfect labels, and production latency. I don't optimise notebooks — I design systems that survive
production, and I measure them honestly.

---

## About me

I enjoy learning new technologies and adapting quickly to different problem domains. I'm comfortable
working across the full ML stack and iterating on systems from prototype to production. I'm a data
enthusiast inside and outside work, always looking for the next challenge.
