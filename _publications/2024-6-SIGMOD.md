---
title: "**Splitting Tuples of Mismatched Entities"
collection: publications
permalink: /publication/2024-6-SIGMOD
date: December, 2023
venue: 'Proceedings of the ACM on Management of Data (SIGMOD)'
paperurl: 'https://dl.acm.org/doi/10.1145/3626763'
citation: 'Fan, Wenfei, Ziyan Han, Weilong Ren, Ding Wang, Yaoshu Wang, Min Xie, and Mengyi Yan. "Splitting Tuples of Mismatched Entities." Proceedings of the ACM on Management of Data 1, no. 4 (2023): 1-29.'
---

### Abstract

There has been a host of work on entity resolution (ER), to identify tuples that refer to the same entity. This paper studies the inverse of ER, to identify tuples to which distinct real-world entities are matched by mistake, and split such tuples into a set of tuples, one for each entity. We formulate the tuple splitting problem. We propose a scheme to decide what tuples to split and what tuples to correct without splitting, fix errors/assign attribute values to the split tuples, and impute missing values. The scheme introduces a class of rules, which embed predicates for aligning entities across relations and knowledge graphs G, assessing correlation between attributes, and extracting data from G. It unifies logic deduction, correlation models, and data extraction by chasing the data with the rules. We train machine learning models to assess attribute correlation and predict missing values. We develop algorithms for the tuple splitting scheme. Using real-life data, we empirically verify that the scheme is efficient and accurate, with F-measure 0.92 on average.
