---
layout: post
title: 'Stochastic-Depth Ambient Occlusion'
authors: 'Jop Vermeer, Leonardo Scandolo, Elmar Eisemann'
category: publication
---

<img src='/assets/publications/VSE21/VSE21.png' width='900px'/>
<br>
<a href="/assets/publications/VSE21/VSE21.pdf" download>Download publication</a>
<br>
<a href="http://graphics.tudelft.nl/Publications-new/2021/VSE21/SDAO-supplementary.pdf" download>Download supplementary material</a>
<br>
<a href="http://graphics.tudelft.nl/Publications-new/2021/VSE21/_SDAO-demo.zip" download>Download demo</a>
<br>
<a href="http://graphics.tudelft.nl/Publications-new/2021/VSE21/SDAO.mp4" download>Download showcase video</a>

### Abstract

Ambient occlusion (AO) is a popular rendering technique that enhances depth perception and realism by darkening locations that are less exposed to ambient light (e.g. corners and creases). In real-time applications, screen-space variants, relying on the depth buffer, are used due to their high performance and good visual quality. However, these only take visible surfaces into account, resulting in inconsistencies, especially during motion. Stochastic-Depth Ambient Occlusion is a novel AO algorithm that accounts for occluded geometry by relying on a stochastic depth map, capturing multiple scene layers per pixel at random. Hereby, we efficiently gather missing information in order to improve upon the accuracy and spatial stability of conventional screen-space approximations, while maintaining real-time performance. Our approach integrates well into existing rendering pipelines and improves the robustness of many different AO techniques, including multi-view solutions.


