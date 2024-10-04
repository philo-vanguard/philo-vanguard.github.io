---
title: "Parallel Rule Discovery from Large Datasets by Sampling"
collection: publications
permalink: /publication/2022-6-SIGMOD
date: June, 2022
venue: 'Proceedings of the 2022 International Conference on Management of Data (SIGMOD)'
paperurl: ''
citation: 'Fan, Wenfei, <strong>Ziyan Han</strong>, Yaoshu Wang, and Min Xie. "Parallel rule discovery from large datasets by sampling." In Proceedings of the 2022 International Conference on Management of Data, pp. 384-398. 2022.'
---
[(Download paper here)](https://philo-vanguard.github.io/files/papers/Rule-Discovery-Sampling-SIGMOD22.pdf)&nbsp;&nbsp;
[(Download slides here)](https://philo-vanguard.github.io/files/slides/Rule-Discovery-Sampling-SIGMOD22.ppt)&nbsp;&nbsp;
[(Download source codes here)](https://github.com/philo-vanguard/PRMiner)

### Abstract

Rule discovery from large datasets is often prohibitively costly. The problem becomes more staggering when the rules are collectively defined across multiple tables. To scale with large datasets, this paper proposes a multi-round sampling strategy for rule discovery. We consider Entity Enhancing Rules (REEs) for collective entity resolution and conflict resolution, which may carry constant patterns and machine learning predicates. We sample large datasets with accuracy bounds α and β such that at least α% of rules discovered from samples are guaranteed to hold on the entire dataset (i.e., precision), and at least β% of rules on the entire dataset can be mined from the samples (i.e., recall). We also quantify the connection between support and confidence of the rules on samples and their counterparts on the entire dataset. To scale with the number of tuple variables in collective rules, we adopt deep Q-learning to select semantically relevant predicates. To improve the recall, we develop a tableau method to recover constant patterns from the dataset. We parallelize the algorithm such that it guarantees to reduce runtime when more processors are used. Using real-life and synthetic data, we empirically verify that the method speeds up REE discovery by 12.2 times with sample ratio 10% and recall 82%.
