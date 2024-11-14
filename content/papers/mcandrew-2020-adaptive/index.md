---
title: "Adaptively stacking ensembles for influenza forecasting with incomplete data"
date: 2021-10-14
authors: ["Thomas C McAndrew", "Nicholas G Reich"]
tags: ["influenza","forecasting","ensemble"]
author: ["Thomas McAndrew", "Nicholas G. Reich"]
description: "Needing no data at the beginning of an epidemic, an adaptive ensemble can quickly train and forecast an outbreak, providing a practical tool to public health officials looking for a forecast to conform to unique features of a specific season."
summary: "Needing no data at the beginning of an epidemic, an adaptive ensemble can quickly train and forecast an outbreak, providing a practical tool to public health officials looking for a forecast to conform to unique features of a specific season."
cover:
    image: "featured.png"
    relative: false
editPost:
    URL: "https://doi.org/10.1002/sim.9219"
    Text: "Statistics in Medicince"

---

---

##### Download

+ [Paper](https://onlinelibrary.wiley.com/doi/full/10.1002/sim.9219?casa_token=bXUekxUYm8sAAAAA%3AFJ1touvTBQ6sMZSQjPiZVpmVP080HEoCOtQgTUaUc93qnierJ_9zW_PCERKPG-9ltvzzwl6BCbFrqA)
+ [Github](https://github.com/tomcm39/adaptively_stacking_ensembles_for_infleunza_forecasting_with_incomplete_data)
---

##### Abstract

Seasonal influenza infects between 10 and 50 million people in the United States every year. Accurate forecasts of influenza and influenza-like illness (ILI) have been named by the CDC as an important tool to fight the damaging effects of these epidemics. Multi-model ensembles make accurate forecasts of seasonal influenza, but current operational ensemble forecasts are static: they require an abundance of past ILI data and assign fixed weights to component models at the beginning of a season, but do not update weights as new data on component model performance is collected. We propose an adaptive ensemble that (i) does not initially need data to combine forecasts and (ii) finds optimal weights which are updated week-by-week throughout the influenza season. We take a regularized likelihood approach and investigate this regularizer’s ability to impact adaptive ensemble performance. After finding an optimal regularization value, we compare our adaptive ensemble to an equal-weighted and static ensemble. Applied to forecasts of short-term ILI incidence at the regional and national level, our adaptive model outperforms an equal-weighted ensemble and has similar performance to the static ensemble using only a fraction of the data available to the static ensemble. Needing no data at the beginning of an epidemic, an adaptive ensemble can quickly train and forecast an outbreak, providing a practical tool to public health officials looking for a forecast to conform to unique features of a specific season.

---

##### Citation

McAndrew T, Reich NG. Adaptively stacking ensembles for influenza forecasting. Stat Med. 2021 Dec 30;40(30):6931-6952. doi: 10.1002/sim.9219. Epub 2021 Oct 14. PMID: 34647627; PMCID: PMC8671371.

```BibTeX
@article{mcandrew2021adaptively,
  title={Adaptively stacking ensembles for influenza forecasting},
  author={McAndrew, Thomas and Reich, Nicholas G},
  journal={Statistics in medicine},
  volume={40},
  number={30},
  pages={6931--6952},
  year={2021},
  publisher={Wiley Online Library}
}

```
---
