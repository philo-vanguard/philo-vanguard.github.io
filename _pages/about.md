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

I am an engineer in [Katana Graph](https://katanagraph.com/), 
the startup based in part on my PhD research. 
The startup was founded in 2020 by 
[Dr. Keshav Pingali](https://www.cs.utexas.edu/~pingali/) and
[Dr. Chris Rossbach](https://www.cs.utexas.edu/~rossbach/).

I received my PhD from the [University of Texas at Austin](https://www.cs.utexas.edu/), 
where I was advised by [Dr. Keshav Pingali](https://www.cs.utexas.edu/~pingali/).
I received my masters from the 
[Indian Institute of Science](http://www.csa.iisc.ac.in/), where I was advised by 
[Dr. Uday Bondhugula](http://drona.csa.iisc.ernet.in/~uday/).

During the summer of 2018 and 2019, I was a research intern in 
[Microsoft Research](https://www.microsoft.com/en-us/research/group/research-in-software-engineering-rise/), 
where I collaborated with several researchers including 
[Dr. Olli Saarikivi](https://www.microsoft.com/en-us/research/people/olsaarik/), 
[Dr. Kim Laine](https://www.microsoft.com/en-us/research/people/kilai/), and 
[Dr. Madan Musuvathi](https://www.microsoft.com/en-us/research/people/madanm/).

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
 we introduce DLB, a \textbf{D}eep \textbf{L}earning based load \textbf{B}alancing mechanism, to effectively address the data skew problem. The key idea of DLB is to replace hash functions in the load balancing mechanisms with deep learning models, which are trained to be able to map different distributions of workloads and data to the servers in a uniformed manner. We implemented DLB and deployed it on a practical Cloud environment using CloudSim. Experimental results using both synthetic and real-world data sets show that compared with traditional hash function based load balancing methods, DLB is able to achieve more balanced mappings, especially when the workload is highly skewed.

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
<!-- I intend to build on this to support  
*distributed and heterogeneous systems for sparse computation 
like graph databases, graph mining, graph embeddings,
sparse deep learning, and mesh-based numerical simulation*. -->

**Modern Hardware for Data governance**: 
High performance entity resolution (ER) is crucial for many data clean and integration tasks.
To speed up ER, we present the design and implementation of a family of ER algorithms that are tuned to exploit various GPU hardware characteristics for working around the two main limitations of GPUs–limited memory capacity and slow PCIe interface. To scale with large datasets beyond the GPU memory and settle  false dependencies that produced delays, we proposed a tasks scheduling model that can dynamically balance workload and expansion computing resources. The experimental evaluation shows that our approach can scale to large data and achieve significantly better performance than popular methods that speed up ER by utilizing  either MapReduce of CPU cluster or GPU-only framework.

**Multicore Machine Graph Processing**: 
Graph pattern mining applications are used in chemical engineering, 
bioinformatics, and social sciences. I have worked on building a 
high-level programming language and runtime system that can execute 
such applications on shared-memory CPUs or a GPU. For graph analytical 
applications, I have worked on improving the performance of graph 
analytics systems on byte-addressable memory like Intel Optane DC Persistent Memory.
I have also compared different language abstractions and 
runtime systems for graph analytics on shared-memory CPUs, and 
identified their performance bottlenecks. 
[[VLDB 2020](https://roshandathathri.github.io/publication/2020-vldb-1),
[VLDB 2020](https://roshandathathri.github.io/publication/2020-vldb-2),
[IISWC 2020](https://roshandathathri.github.io/publication/2020-iiswc-1),
[IISWC 2020](https://roshandathathri.github.io/publication/2020-iiswc-2)]


# News

* Our [DLB: Deep Learning Based Load Balancing](https://roshandathathri.github.io/publication/2021-ipdps) paper was accepted to **IEEE CLOUD 2021**.
