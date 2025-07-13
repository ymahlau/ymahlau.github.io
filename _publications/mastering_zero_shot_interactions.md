---
title: "Mastering zero-shot interactions in cooperative and competitive simultaneous games"
collection: publications
category: conferences
permalink: /publication/mastering_zero_shot_interactions
excerpt: 'Albatross is an extension of AlphaZero for simultaneous games'
date: 2024-07-30
venue: '41st International Conference on Machine Learning (ICML)'
paperurl: 'https://arxiv.org/pdf/2402.03136'
bibtexurl: 'https://ymahlau.github.io/files/a_flexible_framework.bib'
citation: 'Mahlau, Y., Schubert, F. & Rosenhahn, B. (2024, July). Mastering zero-shot interactions in cooperative and competitive simultaneous games. In Proceedings of 41st International Conference on Machine Learning (ICML).'
---
The combination of self-play and planning has achieved great successes in sequential games, for instance in Chess and Go. 
However, adapting algorithms such as AlphaZero to simultaneous games poses a new challenge. 
In these games, missing information about concurrent actions of other agents is a limiting factor as they may select different Nash equilibria or do not play optimally at all. 
Thus, it is vital to model the behavior of the other agents when interacting with them in simultaneous games. 
To this end, we propose Albatross: AlphaZero for Learning Bounded-rational Agents and Temperature-based Response Optimization using Simulated Selfplay. 
Albatross learns to play the novel equilibrium concept of a Smooth Best Response Logit Equilibrium (SBRLE), which enables cooperation and competition with agents of any playing strength. 
We perform an extensive evaluation of Albatross on a set of cooperative and competitive simultaneous perfect-information games. 
In contrast to AlphaZero, Albatross is able to exploit weak agents in the competitive game of Battlesnake. 
Additionally, it yields an improvement of 37.6% compared to previous state of the art in the cooperative Overcooked benchmark.
