---
layout: post
title: The Reduced Immersed Method for Real-Time Fluid-Elastic Solid Interaction and Contact Simulation
category: publication
---

<img src='/assets/publications/BSEH19/BSEH19.png' width='600px'/>
<br>
<a href="/assets/publications/BSEH19/BSEH19.pdf" download>Download publication</a>
<br>
<a href="http://graphics.tudelft.nl/Publications-new/2019/BSEH19/immersed_hires.mp4" download>Download showcase video</a>

### Abstract

We introduce the Reduced Immersed Method (RIM) for the real-time simulation of two-way coupled incompressible fluids and elastic solids and the interaction of multiple deformables with (self-)collisions. Our framework is based on a novel discretization of the immersed boundary equations of motion, which model fluid and deformables as a single incompressible medium and their interaction as a unified system on a fixed domain combining Eulerian and Lagrangian terms. An advantage for real-time simulations resulting from this modeling is that two-way coupling phenomena can be faithfully simulated while avoiding costly calculations such as tracking the deforming fluid-solid interfaces and the associated fluid boundary conditions. Our discretization enables the combination of a PIC/FLIP fluid solver with a reduced-order Lagrangian elasticity solver. Crucial for the performance of RIM is the efficient transfer of information between the elasticity and the fluid solver and the synchronization of the Lagrangian and Eulerian settings. We introduce the concept of twin subspaces that enables an efficient reduced-order modeling of the transfer. Our experiments demonstrate that RIM handles complex meshes and highly resolved fluids for large time steps at high framerates on off-the-shelf hardware, even in the presence of high velocities and rapid user interaction. Furthermore, it extends reduced-order elasticity solvers such as Hyper-Reduced Projective Dynamics with natural collision handling.


