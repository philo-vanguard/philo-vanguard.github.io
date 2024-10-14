---
title: "Discovering Top-k Relevant and Diversified Rules"
collection: publications
permalink: /publication/2025-6-SIGMOD
date: June, 2025
venue: 'Proceedings of the ACM on Management of Data (SIGMOD)'
paperurl: ''
citation: 'Wenfei Fan, <strong>Ziyan Han</strong>, Min Xie, and Guangyi Zhang, 2024. Discovering Top-k Relevant and Diversified Rules. Proceedings of the ACM on Management of Data (SIGMOD), 2(4), pp.1-28.'
---
[(Download paper here)](https://philo-vanguard.github.io/files/papers/Rule-Discovery-Top-k-Diversified-SIGMOD25.pdf)&nbsp;&nbsp;
[(Download slide here)](https://philo-vanguard.github.io/files/slides/Rule-Discovery-Top-k-Diversified-SIGMOD25.pptx)&nbsp;&nbsp;
[(Download source codes here)](https://github.com/philo-vanguard/PTopKDivMiner)


### Abstract

This paper studies the problem of discovering top-k relevant and diversified rules. Given a real-life dataset, it is to mine a set of k rules that are as close to users’ interest as possible, and meanwhile, as diverse to each other as possible. It aims to reduce excessive irrelevant rules commonly returned by rule discovery. As a testbed, we consider Entity Enhancing Rules (REEs), which subsume popular data quality rules as special cases. We train a relevance model to learn users’ prior knowledge, rank rules based on users’ need, and propose four diversity measures to assess the diversity between rules. Based on these measures, we formulate a new discovery problem. We show that the bi-criteria discovery problem is NP-complete and hard to approximate. This said, we develop a practical algorithm for the problem, and prove its approximation bounds under certain conditions. Moreover, we develop optimization techniques to speed up the process, and parallelize the algorithm such that it guarantees to reduce runtime when given more processors. Using real-life data, we empirically verify that on average, the top-10 REEs discovered by our algorithm is able to catch 77.5% of errors detected by the entire set Σall of REEs and achieve F1 = 0.74 for real error detection; moreover, discovering top-ranked REEs is 54.89X faster than mining Σall.
