---
title: "A Cluster-Aggregate-Pool (CAP) Ensemble Algorithm for Improved Forecast Performance of influenza-like illness"
date: 2023-12-01
tags: ["forecasting","ensemble","influenza"]
author: [Ningxi Wei, Wei-Min Huang, Thomas McAndrew]
description: "We propose a novel Cluster-Aggregate-Pool or `CAP' ensemble algorithm that first clusters together individual forecasts, aggregates individual models that belong to the same cluster into a single forecast (called a cluster forecast), and then pools together cluster forecasts via a linear pool."
summary: "We propose a novel Cluster-Aggregate-Pool or `CAP' ensemble algorithm that first clusters together individual forecasts, aggregates individual models that belong to the same cluster into a single forecast (called a cluster forecast), and then pools together cluster forecasts via a linear pool."
cover:
    image: "featured.jpg"
    relative: false
editPost:
    URL: ""
    Text: ""
---

---

##### Download

+ [Paper](https://arxiv.org/abs/2401.00076)

---

##### Abstract
Seasonal influenza causes on average 425,000 hospitalizations and 32,000 deaths per year in the United States. Forecasts of influenza-like illness (ILI) -- a surrogate for the proportion of patients infected with influenza -- support public health decision making. The goal of an ensemble forecast of ILI is to increase accuracy and calibration compared to individual forecasts and to provide a single, cohesive prediction of future influenza. However, an ensemble may be composed of models that produce similar forecasts, causing issues with ensemble forecast performance and non-identifiability. To improve upon the above issues we propose a novel Cluster-Aggregate-Pool or `CAP' ensemble algorithm that first clusters together individual forecasts, aggregates individual models that belong to the same cluster into a single forecast (called a cluster forecast), and then pools together cluster forecasts via a linear pool. When compared to a non-CAP approach, we find that a CAP ensemble improves calibration by approximately 10% while maintaining similar accuracy to non-CAP alternatives. In addition, our CAP algorithm (i) generalizes past ensemble work associated with influenza forecasting and introduces a framework for future ensemble work, (ii) automatically accounts for missing forecasts from individual models, (iii) allows public health officials to participate in the ensemble by assigning individual models to clusters, and (iv) provide an additional signal about when peak influenza may be near.

---


##### Citation

Wei, N., Zhou, X., Huang, W. M., & McAndrew, T. (2023). A Cluster-Aggregate-Pool (CAP) Ensemble Algorithm for Improved Forecast Performance of influenza-like illness. arXiv preprint arXiv:2401.00076.

```
BibTeX
@article{wei2023cluster,
  title={A Cluster-Aggregate-Pool (CAP) Ensemble Algorithm for Improved Forecast Performance of influenza-like illness},
  author={Wei, Ningxi and Zhou, Xinze and Huang, Wei-Min and McAndrew, Thomas},
  journal={arXiv preprint arXiv:2401.00076},
  year={2023}
}
```
---
