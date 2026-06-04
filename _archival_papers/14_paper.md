---
author: Muhammad Rafsan Kabir, Md Shopon, Marina Gavrilova
title: "ReSoFed: Reliability-Guided Model Souping for Robust Federated Learning in Heterogeneous Classroom Environments"
affiliation: Affiliation
spotlight: no
number: 8
---
**Abstract**: Computer vision systems are increasingly used in educational environments to analyze classroom activities and support data-driven learning analytics. However, classroom visual data often contain sensitive student information and cannot be centralized across institutions due to privacy and governance constraints. Federated learning (FL) enables collaborative model training without sharing raw data, but its performance can degrade when visual data originate from heterogeneous capture environments. Under such conditions, unreliable client updates can introduce negative transfer during model aggregation. In this work, we propose ReSoFed, a privacy-preserving, reliability-guided federated aggregation framework designed to improve robustness under heterogeneous classroom environments. The framework estimates the cross-domain generalization capability of client models using a heterogeneous server-held validation set and incorporates this signal into a two-stage aggregation process. Specifically, a greedy model-soup procedure identifies a subset of reliable client models whose weight-space combination improves validation performance, followed by reliability-aware weighted aggregation. Experiments on the SCB dataset across multiple CNN and transformer backbones demonstrate that ReSoFed consistently outperforms standard federated learning baselines under heterogeneous visual conditions while preserving data privacy.

[Poster](posters/CV4Edu-14 Poster.pdf)
