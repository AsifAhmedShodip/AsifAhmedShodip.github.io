---
title: "NiWo: An Augmentation Framework to Enhance ML Performance and Interpretability for Tabular Data with Class Imbalance"
collection: publications
permalink: /publication/2026-niwo-sigkdd
excerpt: 'NiWo is an interpretable augmentation framework for imbalanced tabular data. It optimizes neighborhood instance weights within a fixed augmentation budget, eliminating reliance on costly explanation tools. NiWo outperforms prior augmentation methods across 62 tabular datasets and 7 ML models, especially on class-imbalanced and scarce-instance regimes.'
date: 2026-08-01
venue: 'ACM SIGKDD 2026 (Research Track)'
citation: 'Asif Ahmed, Sakhawat Hossain Saimon, Jianhua Ruan, Ke Yang. (2026). &quot;NiWo: An Augmentation Framework to Enhance ML Performance and Interpretability for Tabular Data with Class Imbalance.&quot; <i>ACM SIGKDD 2026 (Research Track)</i>.'
---

**Authors:** Asif Ahmed, Sakhawat Hossain Saimon, Jianhua Ruan, Ke Yang

**Venue:** ACM SIGKDD 2026 (Research Track)

## Abstract

Various data augmentation methods have been proposed to address class imbalance in Machine Learning (ML) and Artificial Intelligence tasks across multiple data modalities. For tabular data, augmentation methods must be interpretable so that human decision-makers can audit the process (e.g., which neighborhoods are being augmented and why). This is particularly essential for data from high-stakes domains. Previous studies have integrated explanation tools to derive instance-level weights that drive the augmentation process while maintaining interpretability. However, such an integration is computationally expensive for real-world datasets with thousands of instances due to the complexity of explanation tools.

This paper proposes a novel augmentation framework, **NiWo**, that eliminates the need for explanation tools. NiWo optimizes the weights of influential neighborhood instances within an augmentation budget, i.e., the total number of records to be generated, thus preserving computational efficiency and offering interpretability. It implements two optimization strategies and an ensemble method that activates the most appropriate strategy for a given dataset. NiWo decouples budget allocation from instance generation. The latter can be flexibly replaced to maximize improvement in model performance. This also enables augmentation to be audited and adjusted based on domain-specific requirements within a human-in-the-loop framework. Results of **62 tabular datasets and 7 models** show that NiWo outperforms other augmentation methods at enhancing ML performance, especially over datasets with class imbalance and scarce instances.

## Citation

```
Asif Ahmed, Sakhawat Hossain Saimon, Jianhua Ruan, Ke Yang. (2026).
"NiWo: An Augmentation Framework to Enhance ML Performance and
Interpretability for Tabular Data with Class Imbalance."
ACM SIGKDD 2026 (Research Track).
```
