# Alex | ML Systems Engineer

I build production-ready machine learning systems — from raw data to deployed models — designed to be reproducible, testable, and operational in real environments.

Most ML projects fail outside the notebook. I focus on production constraints: data quality, reproducibility, evaluation correctness, and system reliability.

Background in systems administration (ASIR). I design ML systems with infrastructure, failure modes, and performance in mind before model complexity.

---

## What I deliver

- End-to-end ML pipelines (ingestion → validation → feature engineering → training → evaluation → inference)
- Data pipelines with schema validation, quality checks, and leakage prevention
- Reproducible environments with versioned data and locked dependencies (`uv`, Docker)
- Calibrated probability outputs (Brier score, reliability curves), not raw model scores
- Time-aware evaluation frameworks (walk-forward / stratified CV depending on problem type)
- ML systems decoupled from business decision logic
- Batch inference pipelines designed for scheduled production workloads

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

![HDFS](https://img.shields.io/badge/HDFS-FF6F00?style=flat&logo=apache&logoColor=white)
![Hive](https://img.shields.io/badge/Hive-FDEE21?style=flat&logo=apachehive&logoColor=black)
![Sqoop](https://img.shields.io/badge/Sqoop-2C3E50?style=flat&logo=apache&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat&logo=polars&logoColor=white)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)

**Certified:** Microsoft Azure Data Fundamentals · Power BI (DAX)  
[Credly](https://www.credly.com/users/alejandro-cancelas-chapela/badges#credly)

---

## Featured Projects

### [dskit](https://github.com/cacelass/dskit) — Reproducible ML project scaffold

Production-grade ML template designed to eliminate environment drift and enforce consistent project structure.

**Why it matters**  
Most ML failures are not model failures — they are reproducibility and data consistency failures.

**What it enforces**
- Strict project structure (`data/`, `features/`, `models/`, `pipelines/`)
- Dependency locking with `uv`
- Documentation system with Sphinx
- Pandas / Polars interoperability

**Result**  
Faster setup, consistent engineering standards, zero environment ambiguity.

---

### [credit-risk-classifier](https://github.com/cacelass/credit-risk-classifier) — Credit risk scoring system

ML system designed for real decision-making, focused on calibrated probabilities instead of raw predictions.

**Key decisions**
- Logistic Regression + Random Forest for interpretability vs performance trade-off
- Probability calibration (Platt scaling / isotonic regression)
- Decision threshold decoupled from model (business layer owns decision policy)

**Evaluation**
- Stratified k-fold cross-validation
- Brier score + AUC as primary metrics
- Strict leakage prevention across time and folds

**Result**  
AUC: 0.81 with calibrated outputs suitable for operational decision systems.

---

### [stock-market-prediction](https://github.com/cacelass/stock-market-prediction) — Time series under real constraints

ML applied to a non-stationary, low signal-to-noise environment under realistic constraints.

**What most people do wrong**  
Random splits → leakage → inflated performance

**What this project enforces**
- Walk-forward validation (deployment simulation)
- Baseline-first evaluation discipline
- Strict no-leakage constraints

**Result**  
Marginal improvement over baseline, consistent with efficient market behavior.

---

## Positioning

I design ML systems that remain stable under real-world constraints: shifting data distributions, imperfect labels, and production latency.

I don’t optimize notebooks. I design systems that survive production.

---

## About me

I enjoy learning new technologies and adapting quickly to different problem domains. I’m comfortable working across the full ML stack and iterating on systems from prototype to production.
