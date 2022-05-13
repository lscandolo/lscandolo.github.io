---
layout: post
title: 'Program parallelization using synchronized pipelining'
authors: 'Leonardo Scandolo, César Kunz, Manuel Hermenegildo'
category: publication
---

<a href="/assets/publications/SKH09/SKH09.pdf" download>Download publication</a>

### Abstract

While there are well-understood methods for detecting loops whose iterations are independent and parallelizing them, there are comparatively fewer proposals that support parallel execution of a sequence of loops or nested loops in the case where such loops have dependencies among them. This paper introduces a refined notion of independence, called eventual independence, that in its simplest form considers two loops, say loop1 and loop2, and captures the idea that for every i there exists k such that the i + 1-th iteration of loop2 is independent from the j-th iteration of loop1, for all j ≥ k. Eventual independence provides the foundation of a semantics-preserving program transformation, called synchronized pipelining, that makes execution of consecutive or nested loops parallel, relying on a minimal number of synchronization events to ensure semantics preservation. The practical benefits of synchronized pipelining are demonstrated through experimental results on common algorithms such as sorting and Fourier transforms.


