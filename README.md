# Alex | ML Systems Engineer

I build production-ready machine learning systems — from raw data to deployed models — designed to be reproducible, scalable, and usable in real environments.

Most ML projects fail outside the notebook. I focus on what actually matters in production: data pipelines, environment isolation, evaluation rigor, and system reliability.

Background in systems administration (ASIR). I think in terms of infrastructure, failure modes, and performance before model complexity.

---

## What I deliver

- End-to-end ML pipelines (ingestion → features → training → evaluation → output)
- Reproducible environments with versioned dependencies (`uv`, Docker)
- Calibrated probability outputs, not raw model scores
- Evaluation frameworks with strict leakage control
- ML systems decoupled from business decision logic
- Batch scoring pipelines designed for real operational use

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

Production-grade template designed to eliminate environment drift and enforce consistent ML project structure from day one.

**Why it matters**  
Most ML failures are not model failures — they are reproducibility failures.

**What it enforces**
- Structured layout: `data/`, `features/`, `models/`, `pipelines/`
- Dependency locking with `uv`
- Built-in documentation with Sphinx
- Dual support for Pandas / Polars workflows

**Result**  
Faster project setup, consistent structure, zero environment ambiguity.

---

### [credit-risk-classifier](https://github.com/cacelass/credit-risk-classifier) — Credit risk scoring system

Built a classification system that outputs calibrated probabilities for real lending decisions — not just model predictions.

**Key decisions**
- Logistic Regression + Random Forest for interpretability
- Explicit probability calibration (raw scores ≠ probabilities)
- Threshold decoupled from model (business-controlled)

**Evaluation**
- Stratified k-fold cross-validation
- Metric aligned with business decisioning

**Result**  
`AUC: 0.81` with interpretable outputs usable by non-technical stakeholders.

---

### [stock-market-prediction](https://github.com/cacelass/stock-market-prediction) — Time series under real constraints

Explores ML in a low signal-to-noise, non-stationary environment with strict evaluation discipline.

**What most people do wrong**  
Random splits → data leakage → fake performance

**What this project does**
- Walk-forward validation (realistic deployment simulation)
- Baseline comparison enforced
- No leakage tolerated

**Result**  
Marginal improvement over baseline — which is the honest outcome in efficient markets.

---

## Positioning

I don’t build models for notebooks.  
I build systems that survive production.
