---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

**Title**: Superfluid Current across a barrier in a Ring Lattice (work in progress)

**Advisor**: Prof. Yongyong Cai

We consider the current of the stationary points of an energy functional for a Bose-Einstein condensate(BEC) on an ideal ring with $N$ sites. 
Suppose we ramp up a barrier at site $1$, that is, the trapping potential $V_{j}$ in this discrete model will be non-zero only at $V_{1}$.
The energy functional is deformed and the stationary points will shift. The project uses numerical algorithms to detect stationary points with current and explore how the super-current changes in this process. 
Here we take the periodic boundary condition.

We first compute some stationary points with current directly and implement constrained high-index saddle dynamics(CHiSD) algorithm to construct the solution landscape of the system to further explore the stationary points. 

We then use the numerical continuation method(a kind of Newton method to some extent) to trace the stationary points when we increase $V_{1}$ and also the repulsive parameter $g$(In this work, we write our own code of numerical continuation to investigate flexibly). 

We find some extra stationary points with non-zero current in some situations, which we cannot compute directly. The numerical computations also shows that the current will eventually vanish when $V_{1}$ is large enough. And the solution's behavior will be different at different $g$. 
We are now trying to do some theoretical analysis about the phenomenon we find. 

We also pay attention to the linear stability and dynamics of this system. 

***

**Title**: [Numerical Solution of the Complex Gross-Pitaevskii Equation: stationary states and dynamics](https://github.com/xixi2219/CGPE)

**Advisor**: Prof. Yongyong Cai

The complex Gross-Pitaevskii equation is a model to describe the Bose-Einstein condensate (BEC) in the exciton-polaritons system. 
In this project, some properties of solutions of complex GPE are studied. 

Firstly, the stationary radial solutions of the complex GPE are calculated efficiently by the collocation method. 

After that, we use the numerical continuation method to study the change of the former stationary solution with respect to the variations in parameters. This work is completed on [AUTO-07p](http://indy.cs.concordia.ca/auto/).

Finally, after analyzing of linear stability, the dynamics of complex GPE are solved numerically by the Strang-splitting spectral method, and we find that the solution will reach a state with vortex lattices under the parameters at which the system is not stable.
