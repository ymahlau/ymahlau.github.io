---
title: "A flexible framework for large-scale FDTD simulations: open-source inverse design for 3D nanostructures"
collection: publications
category: conferences
permalink: /publication/a_flexible_framework
excerpt: 'Presentation of the open-source framework FDTDX'
date: 2025-03-19
venue: 'SPIE'
paperurl: 'https://arxiv.org/pdf/2412.12360'
bibtexurl: 'https://ymahlau.github.io/files/a_flexible_framework.bib'
citation: 'Mahlau, Y., Schubert, F., Bethmann, K., Caspary, R., Lesina, A. C., Munderloh, M., ... & Rosenhahn, B. (2025, March). A flexible framework for large-scale FDTD simulations: open-source inverse design for 3D nanostructures. In Photonic and Phononic Properties of Engineered Nanostructures XV (Vol. 13377, pp. 40-52). SPIE.'
---
We introduce an efficient open-source python package for the inverse design of three-dimensional photonic nanostructures using the Finite-Difference Time-Domain (FDTD) method. 
Leveraging a flexible reverse-mode automatic differentiation implementation, our software enables gradient-based optimization over large simulation volumes. 
Gradient computation is implemented within the JAX framework and based on the property of time reversibility in Maxwell’s equations. 
This approach significantly reduces computational time and memory requirements compared to traditional FDTD methods. 
Gradient-based optimization facilitates the automatic creation of intricate three-dimensional structures with millions of design parameters, which would be infeasible to design manually. 
We demonstrate the scalability of the solver from single to multiple GPUs through several inverse design examples, highlighting its robustness and performance in large-scale photonic simulations. 
In addition, the package features an object-oriented and user-friendly API that simplifies the specification of materials, sources, and constraints. 
Specifically, it allows for intuitive positioning and sizing of objects in absolute or relative coordinates within the simulation scene. 
By rapid specification of the desired design properties and rapid optimization within the given user constraints, this open-source framework aims to accelerate innovation in photonic inverse design. 
It yields a powerful and accessible computational tool for researchers, applicable in a wide range of use cases, including but not limited to photonic waveguides, active devices, and photonic integrated circuits.
