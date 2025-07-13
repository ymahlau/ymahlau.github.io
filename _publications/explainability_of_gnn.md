---
title: "[Re] On Explainability of Graph Neural Networks via Subgraph Explorations"
collection: publications
category: conferences
permalink: /publication/explainability_of_gnn
excerpt: 'Analysis of the Interpretability of Graph Neural Networks through the SubgraphX algorithm'
date: 2023-07-20
venue: 'ML Reproducibility Challenge 2022'
paperurl: 'https://leokayser.github.io/assets/pdf/papers/%5BRe%5D_On_Explainability_of_Graph_Neural_Networks_via_Subgraph_Explorations.pdf'
bibtexurl: 'https://ymahlau.github.io/files/explainability_of_gnn.bib'
citation: 'Mahlau, Y., Berg, L., & Kayser, L. (2023, July). [Re] On Explainability of Graph Neural Networks via Subgraph Explorations. In ML Reproducibility Challenge 2022.'
---
Yuan et al. claim their proposed method SubgraphX achieves (i) higher fidelity in explaining models for graph‐ and node classification tasks compared to other explanation techniques, namely GNNExplainer. 
Additionally, (ii) the computational effort of SubgraphX is at a ”reasonable level”, which is not further specified by the original authors. 
We define this as at most ten times slower than GNNExplainer.
We reimplemented the proposed algorithm in PyTorch. 
Then, we replicated the experiments performed by the authors on a smaller scale due to resource constraints. 
Additionally, we checked the performance on a new dataset and investigated the influence of hyperparameters. 
Lastly, we improved SubgraphX using greedy initialization and utilizing fidelity as a score function.
We were able to reproduce the main claims on the MUTAG dataset, where SubgraphX has a better performance than GNNExplainer. 
Furthermore, SubgraphX has a reasonable runtime of about seven times longer than GNNExplainer. 
We successfully employed SubgraphX on the Karate Club dataset, where it outperforms GNNExplainer as well. 
The hyperparameter study revealed that the number of Monte‐Carlo Tree search iterations and Monte‐Carlo sampling steps are the most important hyperparameters and directly trade performance for runtime. 
Lastly, we show that our proposed improvements to SubgraphX significantly enhance fidelity and runtime.
