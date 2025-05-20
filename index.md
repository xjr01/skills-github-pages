---
title: Welcome to my blog
---

The Navier-Stoke equations for incompressible fluids are

$$
\frac{\partial\boldsymbol u}{\partial t}+(\boldsymbol u\cdot\nabla)\boldsymbol u=-\frac 1\rho\nabla p+\nu\nabla^2\boldsymbol u+\boldsymbol g,
$$
$$
\nabla\cdot\boldsymbol u&=0.
$$

In fluid simulations, we usually solve this equation with an operator splitting scheme, leading to an algorithm with advection, adding outer forces, projection and diffuse steps.
