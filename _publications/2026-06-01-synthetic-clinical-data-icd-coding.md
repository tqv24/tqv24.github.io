---
title: "Synthetic Clinical Data Generation for Training Robust ICD Coding Models"
collection: publications
category: manuscripts
permalink: /publication/2026-synthetic-clinical-data-icd-coding
excerpt: 'Built a synthetic data pipeline for generating targeted clinical samples for rare ICD codes, improving model robustness.'
date: 2026-06-01
venue: 'Under review at ACL 2026'
paperurl: 'https://arxiv.org/abs/2511.14112'
citation: 'Truong Vo, Weiyi Wu, and Kaize Ding. (2026). Synthetic Clinical Data Generation for Training Robust ICD Coding Models. <i>Under review at the 64th Annual Meeting of the Association for Computational Linguistics (ACL 2026)</i>.'
---

Automatic ICD coding from clinical text is a critical task in medical NLP but remains hindered by the extreme long-tail distribution of diagnostic codes. Thousands of rare and zero-shot ICD codes are severely underrepresented in datasets like MIMIC-III, leading to low macro-F1 scores. In this work, we propose a data-centric framework that generates high-quality synthetic discharge summaries to mitigate this imbalance. Our method constructs realistic multi-label code sets anchored on rare codes by leveraging real-world co-occurrence patterns, ICD descriptions, synonyms, taxonomy, and similar clinical notes. Using these structured prompts, we generate 90,000 synthetic notes covering 7,902 ICD codes, significantly expanding the training distribution. We fine-tune two state-of-the-art transformer-based models, PLM-ICD and GKI-ICD, on both the original and extended datasets. Experiments show that our approach modestly improves macro-F1 while maintaining strong micro-F1, outperforming prior SOTA. While the gain may seem marginal relative to the computational cost, our results demonstrate that carefully crafted synthetic data can enhance equity in long-tail ICD code prediction.


[Download paper here](https://arxiv.org/abs/2511.14112)
