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

I was a research intern in 
[SICS](https://www.microsoft.com/en-us/research/group/research-in-software-engineering-rise/), 
where I collaborated with several researchers including 
[Dr. Shuhao Liu](https://shuhaoliu.github.io), and
[Dr. Min Xie](https://www.microsoft.com/en-us/research/people/kilai/).

# Research Interests

My research interests are broadly in the field of 
**database systems**, **high-performance computing** and **AI for system**
with an emphasis on optimizing runtime systems for 
*distributed* and *heterogeneous* architectures. 
Currently, my focus is on building 
large-scale graph databases and systems by leveraging modern hardware and heterogeneous architectures. 

In recent work, 
I have built a intelligent load balancer for **distributed processing systems**
This work has been published in IEEE CLOUD 2021.
A brief summary of my past work can be found below.

**AI for distributed processing**:
 we introduce DLB, a Deep Learning based load Balancing mechanism, to effectively address the data skew problem. The key idea of DLB is to replace hash functions in the load balancing mechanisms with deep learning models, which are trained to be able to map different distributions of workloads and data to the servers in a uniformed manner. We implemented DLB and deployed it on a practical Cloud environment using CloudSim. Experimental results using both synthetic and real-world data sets show that compared with traditional hash function based load balancing methods, DLB is able to achieve more balanced mappings, especially when the workload is highly skewed.

[[IEEE CLOUD 2021](https://drive.google.com/file/u/0/d 1PpBGov7mavn_xqb21zU7Quo3NnZX78i1/view)]
<!--
[[PLDI 2018](https://roshandathathri.github.io/publication/2018-pldi), 
[ASPLOS 2019](https://roshandathathri.github.io/publication/2019-asplos), 
[VLDB 2018](https://roshandathathri.github.io/publication/2018-vldb), 
[PPoPP 2019](https://roshandathathri.github.io/publication/2019-ppopp), 
[PACT 2019](https://roshandathathri.github.io/publication/2019-pact), 
[IPDPS 2021](https://roshandathathri.github.io/publication/2021-ipdps), 
[IPDPS 2020](https://roshandathathri.github.io/publication/2020-ipdps), 
[IPDPS 2019](https://roshandathathri.github.io/publication/2019-ipdps), 
[IPDPS 2018](https://roshandathathri.github.io/publication/2018-ipdps), 
[Euro-Par 2018](https://roshandathathri.github.io/publication/2018-europar),
[HPEC GraphChallenge 2019](https://roshandathathri.github.io/publication/2019-graphchallenge), 
[BigData 2017](https://roshandathathri.github.io/publication/2017-bigdata)]
-->
<!-- I intend to build on this to support  
*distributed and heterogeneous systems for sparse computation 
like graph databases, graph mining, graph embeddings,
sparse deep learning, and mesh-based numerical simulation*. -->

**Modern Hardware for Data governance**:
High performance entity resolution (ER) is crucial for many data clean and integration tasks. To speed up ER, we present the design and implementation of a family of ER algorithms that are tuned to exploit various GPU hardware characteristics for working around the two main limitations of GPUs–limited memory capacity and slow PCIe interface. To scale with large datasets beyond the GPU memory and settle  false dependencies that produced delays, we proposed a tasks scheduling model that can dynamically balance workload and expansion computing resources. The experimental evaluation shows that our approach can scale to large data and achieve significantly better performance than popular methods that speed up ER by utilizing  either MapReduce of CPU cluster or GPU-only framework.

**Single Machine Graph Processing**: 
Graph pattern mining/analysis applications are used in chemical engineering, 
bioinformatics, and social sciences. I have worked on building a 
high-level programming language and runtime system that can execute 
such applications on shared-memory/out-of-core CPUs or a GPU. For graph analytical 
applications,
I have also compared different language abstractions and 
runtime systems for graph analytics on shared-memory CPUs, and 
identified their performance bottlenecks. 


[[VLDB 2023](https://shuhaoliu.github.io/assets/papers/minigraph-full.pdf)]
<!--
[[VLDB 2020](https://roshandathathri.github.io/publication/2020-vldb-1),
[VLDB 2020](https://roshandathathri.github.io/publication/2020-vldb-2),
[IISWC 2020](https://roshandathathri.github.io/publication/2020-iiswc-1),
[IISWC 2020](https://roshandathathri.github.io/publication/2020-iiswc-2)]
-->

# News

* Our [MiniGraph: Querying Big Graphs with a Single Machine](https://shuhaoliu.github.io/assets/papers/minigraph-full.pdf) paper was accepted to **VLDB 2023**.
* Our [Deep and Collective Entity Resolution in Parallel](https://drive.google.com/file/u/0/d/1PpBGov7mavn_xqb21zU7Quo3NnZX78i1/view) paper was accepted to **ICDE 2022**.
* Our [DLB: Deep Learning Based Load Balancing](https://drive.google.com/file/u/0/d 1PpBGov7mavn_xqb21zU7Quo3NnZX78i1/view) paper was accepted to **IEEE CLOUD 2021**.
