# Model order reduction for bifurcating phenomena in fluid-structure interaction problems

### Master thesis in Mathematical Engineering authored by Khamlich Moaad


Advisor:         Prof. Simona Perotto
Co-advisors:     Prof. Gianluigi Rozza
                 Prof. Claudio Canuto
                 Dr. Federico Pichi
                 
# Abstract

This thesis consists in the development and analysis of an efficient reduced order model
for the study of bifurcation phenomena governed by non-linear PDEs in fluid-structure
interaction problems.
We focused on a particular bifurcating phenomenon known as the Coandă effect, which
concerns the Navier-Stokes equations’ stationary solutions for an incompressible, newto-
nian and viscous fluid. We have chosen to address the particular case of a contraction-
expansion channel because it represents a simplification aimed at analyzing a heart
disease known as mitral valve regurgitation.
The goal of our investigation was to generalize previous works conducted on such com-
plex phenomenon, to understand how it is influenced by the introduction of an elastic
structure at the interface of the fluid resolution domain.
In particular, we have provided a detailed description of the weak formulation associ-
ated with the problem, emphasizing the treatment of coupling conditions and the ALE
formulation, which is needed because of the computational domain’s deformation.
It should be noted that the reconstruction of the bifurcation diagrams related to a non-
linear PDE requires considerable computational effort. That is why we have addressed
the resolution by developing a reduced branch-wise algorithm based on a monolithic
Proper Orthogonal Decomposition (POD) coupled with Galerkin Finite Elements. This
approach optimizes the computational resources and provides results that can be applied
in a multiple parameter context.
