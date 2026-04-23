# Estimator-Aligned Sample Size Determination for IPTW Analyses

This repository provides the R implementation for the paper: 
**"Estimator-Aligned Prospective Sample Size Determination for Designs Using Inverse Probability of Treatment Weighting"**.

The repository contains simulation code to perform pilot-based sample size determination for inverse probability of treatment weighting (IPTW) analyses using stacked estimating equations and sandwich variance estimation.

---

## 🚀 Key Features
* **Estimator-Aligned Design:** Sample size directly targets the asymptotic variance of the IPTW estimator used in analysis.
* **Stacked M-Estimation:** Joint modeling of propensity score and outcome to propagate nuisance uncertainty.
* **Bootstrap Stabilization:** Two-level bootstrap to stabilize the large-sample variance factor (LSVF).
* **Flexible Outcomes:** Supports various outcomes (e.g., binary, count, and continuous outcomes) under a unified framework.
  
---

## 📂 Folder Overview
* `/main`: Simulation code for reproducing the main manuscript results.
* `/supplement`: Simulation code for supplementary results under constant propensity (RCT-like setting).

---

## Reference
If you use this code, please cite the following article:  

Hong, T., Lim, D., Bae, W. & Ma, Y. (2026). Estimator-Aligned Prospective Sample Size Determination for Designs Using Inverse Probability of Treatment Weighting. Arxiv
