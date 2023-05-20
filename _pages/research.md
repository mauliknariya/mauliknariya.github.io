---
layout: archive
title: ""
permalink: /research/
author_profile: true

---

{% include base_path %}

## Paired evaluation for improvevd estimates of performance of machine learning models

The true accuracy of a machine learning model is a population-level statistic that cannot be observed directly. In practice, predictor performance is estimated against one or more test datasets, and the accuracy of this estimate strongly depends on how well the test sets represent all possible unseen datasets. We present a simple approach, paired evaluation, for increasing the robustness of performance evaluation by systematic pairing of test samples, and use it to evaluate predictors of drug response in breast cancer cell lines and of disease severity in patients with Alzheimer’s Disease. Our results demonstrate that the choice of test data can cause variations in estimates of performance and that paired evaluation makes it possible to identify outliers, improve the accuracy of performance estimates in the presence of known confounders, and assign statistical significance when comparing machine learning models.

[paired-eval repo](https://github.com/labsyspharm/paired-eval)

<img src="/files/lpocv_schematic.png" 
        alt="Picture" 
        width="800" 
        style="display: block; margin: 0 auto" />

## Mathematical models for length control in bacterial structures

Bacterial cells construct many structures, such as the flagellar hook and the type III secretion system (T3SS) injectisome, that aid in crucial physiological processes.The length of these channels must be highly regulated in order for these structures to perform their intended functions. There are two leading mechanisms for length regulation in the flagellar hook and T3SS needle: the substrate switching mechanism, in which the length is controlled by assembly of an inner rod, and the ruler mecchanism, in which a molecular ruler controls the length. Using principles from dynamical systems, probability theory, and Gillespie algorithm, we developed mathematical models for these mechanisms. Our models suggest that for the susbtrate switching mechanism the variance in length distribution of these structures would scale quadractically with the average length, whereas for the ruler mechanism the variance would scale linearly with the average length. These findings shed new light on the trade-offs that may have led to the evolution of different length control mechanisms in different bacterial species.

| Ruler mechanism | Substrate switching mechanism |
| :-----------------------------------------------------: | :---------------------------------------------: |
| <img src="/files/ruler_model.jpg" width="500"/> | <img src="/files/substrate_switching.png" width="500"/> |


