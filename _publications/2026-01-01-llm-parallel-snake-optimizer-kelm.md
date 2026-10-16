---
title: "A Novel Parallel Snake Optimizer with LLM-Enhanced Cross-Population Communication for KELM Hyperparameter Optimization and Applied in Power Load Forecasting"
collection: publications
permalink: /publication/2026-01-01-llm-parallel-snake-optimizer-kelm
date: 2026-01-01
venue: 'IEEE Transactions on Industry Applications'
category: manuscripts
paperurl: 'https://doi.org/10.1109/TIA.2026.3721836'
citation: '<b>Tian-Yu Gao</b><sup>*</sup>, <b>Gao-Yuan Liu</b><sup>*</sup>, Joel J. P. C. Rodrigues, Philipp Koehn, Jeng-Shyang Pan, Hui-Qi Zhao, Ying Yu, Ru-Yu Wang. &quot;A Novel Parallel Snake Optimizer with LLM-Enhanced Cross-Population Communication for KELM Hyperparameter Optimization and Applied in Power Load Forecasting.&quot; <i>IEEE Transactions on Industry Applications</i>, 2026. (<sup>*</sup>equal contribution; co-first authors. DOI: 10.1109/TIA.2026.3721836)'
excerpt: 'An LLM serves as an online strategy scheduler inside a parallel multi-population snake optimizer, adaptively selecting cross-population communication operators to tune KELM hyperparameters for short-term power load forecasting.'
---

A large language model (DeepSeek-V3.2) is embedded as an online scheduler in a parallel multi-population snake optimizer: it reads a global search-state vector (iteration progress, subpopulation fitness, diversity and convergence trends) and, every 20 iterations, selects cross-population communication strategies from a ten-operator library to balance exploration and exploitation. The tuned kernel extreme learning machine (regularization C, kernel bandwidth γ, kernel type, polynomial degree) is optimized under a composite fitness combining scale-invariant error (NRMSE) with an asymmetric penalty that weights over-prediction more heavily. On the GEFCom2012 short-term load forecasting benchmark the method attains the best MAE, RMSE, NRMSE, MAPE and R² among all compared metaheuristically optimized KELM and baseline deep learning models.

[Code](https://github.com/leogalaxy0603/LLM-Parallel-SO-for-KELM)
