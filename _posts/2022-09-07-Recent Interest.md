---
layout: post
title: "Recent Interesting Papers"
subtitle: "Topology, Entanglement, and All That"
author: "Yingfei Gu"
#header-img: "img/thisfilename/head.jpg" # if you have a header image. or if you want to have a text style head, see the next line
#header-style: T1 
#header-mask: 0.4
mathjax: true # if you have equations in your article
#tags:
#  - Test
#  - tag2
---

注意到几篇很有意思的文章：

1. 关于  Fermi Sea Topology 
    * Quantized Nonlinear Conductance in Ballistic Metals https://arxiv.org/abs/2108.05870
    * Topological Multipartite Entanglement in a Fermi Liquid https://arxiv.org/abs/2204.06559

    第一篇文章是Charles L. Kane的“居家防疫之作”（某次报告中提及，不知是否是玩笑话）。简单的说，他推广了一维的Landauer formula到一般维度，角度很独特。文章读起来有种“清爽”的感觉，一如他过去拓扑绝缘体的那些经典之作。技术上运用了Morse theory这个物理学家屡试不爽的技巧（在凝聚态中的经典成功案例是van Hove singularity），将一个很自然的输运系数和Fermi sea的欧拉示性数联系起来。他提出的公式是如此自然，让人很难相信这样简单的公式在之前没有被发现。我想，这大概是Kane的独特眼光和魅力吧。

    第二篇粗读我觉得写的很好，里面有很多有意思的计算和漂亮的结论。它将Fermi sea的拓扑用量子纠缠来表达，比上一篇更有意思。更进一步的是，他们发现虽然相互作用会破坏一些输运系数（例如上一篇中利用的非线性电导）的量子/离散化，但是对利用量子纠缠来表达的公式，至少可以微绕地证明没有影响，这件事很神秘，也很深刻。


2. 关于 Modular (Entanglement) Hamiltonian
    * Chiral central charge from a single bulk wave function https://arxiv.org/abs/2110.06932
    * Modular commutator in gapped quantum many-body systems https://arxiv.org/abs/2110.10400

    这两篇讲的是一回事（后者是前者的重复和细节版），关于如何从modular Hamiltonian得到热霍尔效应系数（反映到边界上并假设共形对称性，则是边界态的chiral central charge $c_-$）的一个猜想

    $$i\langle \psi | [K_{AB},K_{BC}] |\psi \rangle = \frac{\pi}{3} c_- $$

    其中 $|\psi\rangle$ 是某个二维有能隙哈密顿量的基态，$K_{X}$ 是某个子区域 $X$ 的modular Hamiltonian，ABC是三个逆时针展开交于一点的三个足够大的子区域（详情请参考上述链接）。

    这个公式很有趣，但作者并没有给出足够令人信服的证据证明其普适性。很有可能未来会有更准确的版本出现，在某个特殊条件下回到上述公式。尤其对于无限维希尔伯特空间的情形，例如量子场论，上述公式中的modular Hamiltonian并不是良好定义的。但不管怎么样，这个公式的含义值得思考。


上述的工作有个共同特点就都可以从自由费米子出发得到基本的结论，但是应用范围又更广一些，非常适合初入该领域的学生加深理解。
