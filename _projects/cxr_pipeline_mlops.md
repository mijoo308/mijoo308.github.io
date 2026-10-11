---
layout: page
title: Chest X-ray Data Pipelines & MLOps
description: Airflow data pipelines, experiment tracking, and a SLURM-based multi-node GPU cluster for medical AI research
importance: 4
category: engineering
---

Research is only as fast as its infrastructure. At VUNO's chest X-ray team, I work on the data and training infrastructure that medical AI research runs on:

- **Airflow data pipelines** for consolidating large-scale, multi-institutional chest X-ray datasets under a unified schema, including a FastAPI-based plugin with a web UI for human inspection of pipeline outputs — with roughly **2× improvements in processing time and memory usage** through pipeline optimization
- **Experiment tracking and HPO**: migrating experiment management to Weights & Biases and parallelizing hyperparameter optimization
- **GPU cluster scheduling**: designed and validated a **SLURM-based multi-node GPU cluster**, including multi-node distributed (DDP) training PoC and fractional GPU sharing experiments
