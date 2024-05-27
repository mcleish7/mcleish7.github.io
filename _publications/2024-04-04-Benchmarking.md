---
title: "[Re] End-to-End Algorithm Synthesis with Recurrent Networks: Logical Extrapolation Without Overthinking"
collection: publications
permalink: /publications/2023-08-02-Re-End-to-End
excerpt: 'In this report, we aim to validate the claims of Bansal et al. These are that the recurrent architecture presented, with skip connections and a progressive loss function, prevent the original problem being forgotten or corrupted during processing allowing for the recurrent module to be applied indefinitely and that this architecture avoids the overthinking trap. We use both code released by the authors and newly developed to recreate many results presented in the paper. Additionally, we present analysis of the newly introduced alpha hyperparameter and investigate interesting perturbation behaviour of prefix sums models. Further, we conduct a hyperparameter search and provide an analysis of the Asymptotic Alignment scores of the models presented.'
date: 2023-08-02
venue: 'ReScience Volume 9 Issue 2, Joural to Conference Track NeurIPS 2023'
paperurl: 'https://openreview.net/pdf?id=WaZB4pUVTi'
citation: 'Sean Michael McLeish and Long Tran-Thanh, McLeish (2023). &quot;[Re] End-to-end Algorithm Synthesis with Recurrent Networks: Logical Extrapolation Without Overthinking.&quot; <i>ReScience Volume 9 Issue 2</i>.'
---
We evaluate ChatGPT's ability to solve algorithm problems from the CLRS benchmark suite that is designed for GNNs. The benchmark requires the use of a specified classical algorithm to solve a given problem. We find that ChatGPT outperforms specialist GNN models, using Python to successfully solve these problems. This raises new points in the discussion about learning algorithms with neural networks and how we think about what out of distribution testing looks like with web scale training data.

[Download paper here](https://arxiv.org/abs/2404.03441)

[GitHub Code](https://github.com/mcleish7/CLRS4LM)

<!-- title: "Benchmarking ChatGPT on Algorithmic Reasoning"
collection: publications
permalink: /publications/2024-04-04-Benchmarking
excerpt: 'We evaluate ChatGPT's ability to solve algorithm problems from the CLRS benchmark suite that is designed for GNNs. The benchmark requires the use of a specified classical algorithm to solve a given problem. We find that ChatGPT outperforms specialist GNN models, using Python to successfully solve these problems. This raises new points in the discussion about learning algorithms with neural networks and how we think about what out of distribution testing looks like with web scale training data.'
date: 2024-04-04
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2404.03441'
citation: 'Sean Michael McLeish, Avi Schwarzschild and Tom Goldstein, McLeish (2024). &quot;Benchmarking ChatGPT on Algorithmic Reasoning.&quot; <i>arXiv preprint arXiv:2404.03441.</i>.' -->