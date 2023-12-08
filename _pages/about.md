---
permalink: /
title: "Homepage"
excerpt: "Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /~roshan/
---

I am a Phd candidate at [Beihang University](https://ev.buaa.edu.cn/), supervised by [Prof. Wenfei Fan](https://homepages.inf.ed.ac.uk/wenfei/).

I received my masters from the 
[Yunnan University](http://english.ynu.edu.cn/), where I was advised by 
[Prof. Wei Zhou](http://drona.csa.iisc.ernet.in/~uday/),
[Prof. Shaowen Yao](http://drona.csa.iisc.ernet.in/~uday/).

During 2021 - 2024, I was a research intern in 
[Shenzhen Institute of Computing Science](https://en.sics.ac.cn), 
where I collaborated with several researchers including 
[Dr. Shuhao Liu](https://shuhaoliu.github.io), and
[Dr. Min Xie](https://en.sics.ac.cn/en/col130/337).

# Research Interests

My research interests are broadly in the field of 
**database systems**, **graph computing** and **data quality**
with an emphasis on optimizing runtime systems under 
*single machine* and *heterogeneous* architectures. 
Currently, my focus is on building 
large-scale graph databases and systems by leveraging modern hardware and heterogeneous architectures. 


**Data Quality**:
Data quality has always been a key concern in relational and graph databases. High-quality data can greatly improve the accuracy of data analysis, data mining, recommendation systems, and machine learning. On the one hand, existing methods usually mine rules and ask users to confirm them to detect and repair data. There are two problems to be solved: (1) Rule mining/conducting is a complex process. (2) Existing rule mining methods often return a large number of rules, and it is difficult for users to find useful rules for business. On the other hand, entity resolution, as a key technology of data integration, can fuse the same data entity from different data sources to eliminate data redundancy and ensure data quality. However, due to the shortcomings of current entity resolution technology (unable to achieve 100% accuracy), different data entities are easily merged together incorrectly. How to effectively identify and separate these misfused data entities, deduce and complete their correct attribute information has not been paid attention and studied by the industry for the time being. 
Based on the above problems, I mainly study how to use efficient methods to mine/conduct rules on massive data to ensure that the recall rate remains at a high level with certain theoretical guarantees. Parallel and scalable  algorithm was proposed to deal with massive data.

[
  [ICDE 2022](https://drive.google.com/file/d/1PpBGov7mavn_xqb21zU7Quo3NnZX78i1/view),
  [ICDE 2024](https://drive.google.com/file/d/1PpBGov7mavn_xqb21zU7Quo3NnZX78i1/view)
]

**Single Machine Graph Processing**: 
The analysis and processing of large-scale graph data requires a large amount of computing resources. Distributed parallel graph computing can use a large number of computing nodes to improve computing power, but it often does not have parallel scalability due to the limited network communication bandwidth between nodes. For some graph analysis applications, using more compute nodes can even lead to performance degradation. On the other hand, with the development of hardware technology, chip-level parallel architectures such as multi-core multi-processors and multi-Gpus have gradually become the mainstream of commercial use, while the innovation of memory technologies such as non-Uniform Memory Access (NUMA) and non-volatile Memory (NVM) will also improve the processing capacity of traditional shared-memory graph computing systems. Inspired by this, we plan to study and design a new single machine graph computing systems to efficiently use the computing resources of the chip-level parallel architecture and improve the support ability of the single-machine system for large-scale graph computing. 

[[VLDB 2023](https://shuhaoliu.github.io/assets/papers/minigraph-full.pdf)]


# News

* Our [HyperBlocker: Accelerating Rule-based Blocking in Entity Resolution using GPUs](https://shuhaoliu.github.io/assets/papers/minigraph-full.pdf) paper was accepted to **ICDE 2024**.
* Our [MiniGraph: Querying Big Graphs with a Single Machine](https://shuhaoliu.github.io/assets/papers/minigraph-full.pdf) paper was accepted to **VLDB 2023**.
* Our [Deep and Collective Entity Resolution in Parallel](https://drive.google.com/file/u/0/d/1PpBGov7mavn_xqb21zU7Quo3NnZX78i1/view) paper was accepted to **ICDE 2022**.
* Our [DLB: Deep Learning Based Load Balancing](https://drive.google.com/file/u/0/d 1PpBGov7mavn_xqb21zU7Quo3NnZX78i1/view) paper was accepted to **CLOUD 2021**.
