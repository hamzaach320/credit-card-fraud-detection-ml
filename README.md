# 🛡️ Credit Card Fraud Detection Using Machine Learning
### Hybrid LightGBM + LSTM Ensemble with SHAP Explainability

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://python.org)
[![LightGBM](https://img.shields.io/badge/LightGBM-4.x-green)](https://lightgbm.readthedocs.io)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15-orange?logo=tensorflow)](https://tensorflow.org)
[![SHAP](https://img.shields.io/badge/SHAP-0.45-red)](https://shap.readthedocs.io)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

> **AF3008 — Business Research & Data Mining**  
> FAST NUCES Islamabad | Spring 2026  
> Ch Hamza Ahmed Murtaza — i235515@isb.nu.edu.pk

---

## 📊 Results at a Glance

| Metric | LightGBM | LSTM | **Ensemble** |
|--------|----------|------|-------------|
| AUC-ROC | 0.9468 | 0.9723 | **0.9686** |
| F1-Score | 0.003 | 0.074 | **0.752** |
| Precision | 0.002 | 0.039 | **0.711** |
| Recall | 1.000 | 0.892 | **0.797** |
| Avg Precision | 0.287 | 0.751 | **0.720** |

> The ensemble achieves the best F1, Precision, and Recall simultaneously —  
> catching **59 of 74 fraud cases** with only **24 false alarms** in 42,648 transactions.

---

## 🎯 Project Overview

Financial fraud costs the global economy **over $30 billion annually**.
Traditional rule-based systems fail because they:
- Generate excessive false positives
- Miss novel fraud patterns
- Cannot scale to modern transaction volumes

This project proposes a complete ML pipeline that solves these problems
through a hybrid stacking ensemble with explainability.

---

## 🏗️ System Architecture

The pipeline consists of 5 layers:
