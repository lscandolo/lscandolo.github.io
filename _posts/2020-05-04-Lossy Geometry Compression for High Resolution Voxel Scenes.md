---
layout: post
title: Lossy Geometry Compression for High Resolution Voxel Scenes
authors: 'Remi van der Laan, Leonardo Scandolo, Elmar Eisemann'
category: publication
---

<img src='/assets/publications/VSE20/VSE20.png' width='900px'/>
<br>
<a href="/assets/publications/VSE20/VSE20.pdf" download>Download publication</a>
<br>
<a href="/assets/publications/VSE20/VSE20-sup.pdf" download>Download supplementary material</a>
<br>
<a href="http://graphics.tudelft.nl/Publications-new/2020/VSE20/LossyGeometryCompressionForHighResolutionVoxelScenes-supplementary.mp4" download>Download showcase video</a>

### Abstract

Sparse Voxel Directed Acyclic Graphs (SVDAGs) losslessly compress highly detailed geometry in a highresolution binary voxel grid by identifying matching elements. This representation is suitable for highperformance real-time applications, such as free-viewpoint videos and high-resolution precomputed shadows. In this work, we introduce a lossy scheme to further decrease memory consumption by minimally modifying the underlying voxel grid to increase matches. Our method efficiently identifies groups of similar but rare subtrees in an SVDAG structure and replaces them with a single common subtree representative. We test our compression strategy on several standard voxel datasets, where we obtain memory reductions of 10% up to 50% compared to a standard SVDAG, while introducing an error (ratio of modified voxels to voxel count) of only 1% to 5%. Furthermore, we show that our method is complementary to other state of the art SVDAG optimizations, and has a negligible effect on real-time rendering performance.



