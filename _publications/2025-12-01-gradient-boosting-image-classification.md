---
title: "Tricks and Plug-ins for Gradient Boosting in Image Classification"
collection: publications
category: conferences
permalink: /publication/2025-gradient-boosting-image-classification
excerpt: 'Developed a feature-prioritized boosting algorithm (Subgrid-BoostCNN) that accelerates CNN ensemble training by 40%.'
date: 2025-12-01
venue: 'IEEE International Conference on Big Data (BigData 2025)'
paperurl: 'https://arxiv.org/abs/2507.22842'
citation: 'Biyi Fang, Truong Vo, Jean Utke, and Diego Klabjan. (2025). Tricks and Plug-ins for Gradient Boosting in Image Classification. <i>Proceedings of the 2025 IEEE International Conference on Big Data</i>.'
---

Convolutional Neural Networks (CNNs) have achieved remarkable success across a wide range of machine learning tasks by leveraging hierarchical feature learning through deep architectures. However, the large number of layers and millions of parameters often make CNNs computationally expensive to train, requiring extensive time and manual tuning to discover optimal architectures. In this paper, we introduce a novel framework for boosting CNN performance that integrates dynamic feature selection with the principles of BoostCNN. Our approach incorporates two key strategies: subgrid selection and importance sampling, to guide training toward informative regions of the feature space. We further develop a family of algorithms that embed boosting weights directly into the network training process using a least squares loss formulation. This integration not only alleviates the burden of manual architecture design but also enhances accuracy and efficiency. Experimental results across several fine-grained classification benchmarks demonstrate that our boosted CNN variants consistently outperform conventional CNNs in both predictive performance and training speed.
