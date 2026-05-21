# HBAAC Retail Time-Series Forecasting Project

## 1. Project Overview
Welcome to the **HBAAC Time-Series Forecasting** project. The goal of this project is to build a robust, production-ready machine learning pipeline to forecast daily transaction quantities for a retail system spanning **15,972 SKUs** across two distinct 28-day forecasting horizons:
- **Validation Window**: Daily demand forecasting for days F1 to F28.
- **Evaluation Window**: Daily demand forecasting for days F29 to F56 (represented in the submission structure as days F1 to F28 in the `_evaluation` rows).

This competition involves massive scale demand forecasting (15k+ products over multiple years), high sparsity (many zero-demand days), and negative quantity anomalies representing returned transactions.

---

## 2. Directory Structure
