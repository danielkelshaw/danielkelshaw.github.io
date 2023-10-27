---
hide:
    - navigation
    - toc
    - path

title: Software
---

### <a href="https://github.com/danielkelshaw/riemax">Riemax</a>

Riemax is a JAX library for Riemannian geometry, providing the ability to define induced metrics and operate on manifolds directly. Notably, the exponential and logarithmic maps can be computed on arbitrary, differentiable manifolds using a number of methods. This library forms the basis for my current research. You can find the documentation <a href="https://riemax.danielkelshaw.com">here</a>.


### <a href="https://github.com/magrilab/kolsol">KolSol</a>

KolSol implements a differentiable pseudo-spectral solver for the Navier-Stokes equations; or more specifically, the Kolmogorov flow. This library allows the user to interface the solver with machine learning models, as backpropogation can be conducted directly through the solve, a consequence of the `torch` implementation. My research efforts are now focused on producing code in JAX, so an alternative interface will soon become available.


### <a href="https://github.com/magrilab/picr">PICR</a>

PICR provides an implementation of my research on physics-informed removal of corruption from observations on dynamical systems. Employing differentiable solvers, we are able to use a physics-informed approach to find underlying solutions to partial differential equations in absence of ground-truth observations.


### <a href="https://github.com/magrilab/pisr">PISR</a>

PISR provides an implementation of my research on physics-informed super-resolution. Literature in the field of super-resolution focuses primarily on data-driven approaches, assuming access to high-resolution examples. In many scenarios this is not the case, and so we develop a physics-informed approach which allows for recovery of solutions from partial observations.
