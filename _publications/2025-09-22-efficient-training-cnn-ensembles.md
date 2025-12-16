---
title: "Efficient Training of CNN Ensembles via Feature-Prioritized Boosting"
collection: publications
category: conferences
permalink: /publication/2025-efficient-training-cnn-ensembles
excerpt: 'Subgrid-boosted CNN ensembles improve training speed and accuracy by focusing on informative features and integrating boosting into the learning process.'
date: 2025-09-22
venue: 'NeurIPS 2025 Workshop on Optimization'
paperurl: 'https://openreview.net/pdf?id=0vqMsBRXwv'
citation: 'Biyi Fang, Truong Vo, Jean Utke, and Diego Klabjan. (2025). Efficient Training of CNN Ensembles via Feature-Prioritized Boosting. <i>NeurIPS 2025 Workshop on Optimization</i>.'
---

Convolutional Neural Networks (CNNs) have achieved remarkable success in computer vision, yet training deep architectures with millions of parameters remains computationally expensive and design-intensive. We present a novel framework for efficient optimization of CNN ensembles that integrates subgrid-boosted feature selection with boosting-inspired learning. Our method introduces subgrid selection and importance sampling to emphasize statistically informative regions of the feature space, while embedding boosting weights directly into the ensemble training process through a least squares formulation. This design accelerates convergence, reduces the burden of manual architecture tuning, and enhances predictive performance. Across multiple fine-grained image classification benchmarks, our subgrid-boosted CNN ensembles consistently outperform conventional CNNs in both accuracy and training efficiency, demonstrating the effectiveness and generality of the proposed approach.

[Download paper here](https://openreview.net/pdf?id=0vqMsBRXwv)
