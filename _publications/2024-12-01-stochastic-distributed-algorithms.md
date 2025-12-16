---
title: "Stochastic Large-Scale Machine Learning Algorithms with Distributed Features and Observations"
collection: publications
category: conferences
permalink: /publication/2024-stochastic-distributed-algorithms
excerpt: 'Developed the SODDA algorithm for efficient large-scale optimization under both feature and observation partitioning.'
date: 2024-12-01
venue: 'IEEE International Conference on Big Data (BigData 2024)'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10825730'
citation: 'Biyi Fang, Diego Klabjan, and Truong Vo. (2024). Stochastic Large-Scale Machine Learning Algorithms with Distributed Features and Observations. <i>Proceedings of the 2024 IEEE International Conference on Big Data</i>.'
---

As the size of modern datasets exceeds the disk and memory capacities of a single computer, machine learning practitioners have resorted to parallel and distributed computing. Given that optimization is one of the pillars of machine learning and predictive modeling, distributed optimization methods have recently garnered ample attention, in particular when either observations or features are distributed, but not both. We propose a general stochastic algorithm where observations, features, and gradient components can be sampled in a double distributed setting, i.e., with both features and observations distributed. Very technical analyses establish convergence properties of the algorithm under different conditions on the learning rate (diminishing to zero or constant). Computational experiments in Spark demonstrate a superior performance of our algorithm versus a benchmark in early iterations of the algorithm, which is due to the stochastic components of the algorithm.
