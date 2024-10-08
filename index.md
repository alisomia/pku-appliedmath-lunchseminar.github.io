# PKU Applied Math Lunch Seminar

## 应用数学青年讨论班（午餐会）日程表

本学期（2024秋）应用数学拔尖计划将开展午餐会，本学期由**吴清玉**和**沈城烽**同学负责。
往期日程可以参考：[2024年春](2024Spring.html) [2023年秋](2023Fall.html)

本学期日程如下：

1. Sep 11

    **王泽昊**, UCSD

    题目：声音合成与处理中的高效计算：问题、技术及其在当代音乐与声音艺术中的应用

    <details>
    <summary>具体信息</summary>
    
    <p>
    <b>摘要</b>:

    随着电子和数字技术的兴起，音乐和声音艺术经历了巨大的变革。与传统的大规模计算挑战不同，计算在音乐和声音艺术中的应用面临着独特的限制，例如对实时性和交互性的需求、在低功耗微控制器上实现的必要性，以及在精确性与听觉感知之间的微妙平衡。在此次演讲中，我将重点探讨当代音乐和声音艺术中的声音合成与处理的高效计算。我将首先介绍计算在这些艺术领域中的应用，特别是在声音合成与处理方面。随后，我将讨论各种算法及其在不同硬件平台上的实现，结合我在物理建模声音合成和乐器设计方面的研究与实践。最后，我将分享我对这些较为成熟的技术在音乐和声音艺术实践中潜在应用的看法。
    </p>
    <p>
    <b>报告人信息</b>:

    王泽昊是一名计算机音乐研究者和实践者，常驻于圣地亚哥和上海。他目前是加州大学圣地亚哥分校（UCSD）音乐系的计算机音乐博士候选人，导师为Tom Erbe教授和Miller Puckette教授，同时也在上海纽约大学（NYU Shanghai）担任Alex Ruthmann教授的访问研究员。此前，他在北京大学数学科学学院获得了学士学位。他的研究涵盖了音乐声学、声音合成和乐器设计，并与斯坦福大学CCRMA、爱丁堡大学和纽约大学等知名机构的艺术家和研究人员紧密合作。他的研究曾在包括斯坦福大学CCRMA、罗切斯特大学以及斯德哥尔摩皇家音乐学院在内的多个国际场合进行展示。王泽昊也是一位活跃的作曲家和声音设计师，特别专注于戏剧艺术领域。他为戏剧艺术创作的作曲与声音设计曾在北京和纽约市上演。
    </p>
    
    </details>

1. ~~Sep 18~~
1. Sep 25

    **陈畅**, 北京大学
    
    题目：Centauri: Enabling Efficient Scheduling for Communication-Computation Overlap in Large Model Training via Communication Partitioning

    <details>
    <summary>具体信息</summary>
    <p>
    <b>摘要</b>:

    Efficiently training large language models (LLMs) necessitates the adoption of hybrid parallel methods, integrating multiple communications collectives within distributed partitioned graphs. Overcoming communication bottlenecks is crucial and is often achieved through communication and computation overlaps. However, existing overlap methodologies tend to lean towards either fine-grained kernel fusion or limited operation scheduling, constraining performance optimization in heterogeneous training environments.
    In this talk, we introduce Centauri, an innovative framework that encompasses comprehensive communication partitioning and hierarchical scheduling schemes for optimized overlap. We propose a partition space comprising three inherent abstraction dimensions: primitive substitution, topology-aware group partitioning, and workload partitioning. To determine the efficient overlap of communication and computation operators, we decompose the scheduling tasks in hybrid parallel training into three hierarchical tiers: operation, layer, and model. Through these techniques, our framework Centauri effectively overlaps communication latency and enhances hardware utilization.
    </p>
    <p>
    <b>报告人信息</b>:

    陈畅是北京大学前沿交叉学科研究院的博士研究生，导师为杨超。她的研究方向为高性能与分布式计算，大规模机器学习系统和分布式系统。她在本次报告的工作获得了ASPLOS 2024 Best Paper award。

    </p>
    </details>


1. ~~Oct 2~~ (假期)
1. Oct 9

    **张东航**，中国科学院数学与系统科学研究院，博士后

    题目：p-Multigrid method for elliptic problem

    <details>
    <summary>具体信息</summary>
    <p>
    <b>摘要</b>:

    In this talk, we propose the two-level and W-cycle algorithms of p-multigrid method designed to solve the linear systems of equations generated from p-version symmetric interior penalty discontinuous Galerkin (SIPDG) discretizations for elliptic problems. This SIPDG discretization employs hierarchical Legendre polynomial basis functions, where we can design restriction and prolongation operators between different discrete polynomial spaces naturally. Inspired by the uniform convergence theory of the W-cycle algorithm of hp-multigrid method in [P. F. Antonietti, et.al., SIAM J. Numer. Anal., 53 (2015)], we extend their work by providing a more refined matrix-based analysis. Specifically, we estimate the spectral radius of the stiffness matrix and its diagonal matrix, assess the approximation property of coarsest level correction, and analyze the smoothing properties of polynomial smoother based on fourth-kind Chebyshev polynomial iterative method. Building on these foundations, we provide a rigorous matrix-based convergence analysis for the proposed p-multigrid method, considering both inherited and non-inherited bilinear forms of SIPDG discretization. Our theoretical results show significant improvement over [P. F. Antonietti, et.al., SIAM J. Numer. Anal., 53 (2015)], reducing the required number of smoothing steps from O(p^2) to O(p), where p is the polynomial degree of the discrete broken polynomial space. Moreover, the convergence rate remains independent of the mesh size. Finally, several numerical experiments are presented to validate our theoretical findings.
    </p>
    <p>
    <b>报告人信息</b>:

    张东航，2015-2020 中国科学院数学与系统科学院，计算数学博士；2020-2023北京大学北京国际数学研究中心，博士后; 2023年至今，中国科学院数学与系统科学研究院基础软件研究中心。

    </p>
    </details>
1. Oct 16

   **王修远**，北京大学

   TBA
1. Oct 23

   **李世凤**，武汉大学，博士后

   TBA
1. Oct 30
1. Nov 6
1. Nov 13
1. Nov 20
1. Nov 27
1. Dec 4
1. Dec 11
1. Dec 18
1. Dec 25
1. Jan 1
1. Jan 8






-----
This webpage is maintained by Ting Lin (@alisomia)
