---
title: 'New publication in arXiv!'
date: 2025-02-26
permalink: /posts/2026-08-20-HELIOS_arXiv
tags:
  - research article
  - Surface Integral Equations
  - Boundary Element Method
  - stratified media
  - light scattering
  - arXiv
---

Exciting news for the nanophotonics and computational electromagnetics communities!

I'm thrilled to share a new arXiv preprint detailing HELIOS (HomogEneous and Layered medIa Optical Scattering), a new powerful open-source software for modeling light scattering. Developed by myself, under the supervision of Prof. Olivier J.F. Martin at EPFL's Nanophotonics and Metrology Laboratory (NAM), this tool serves as a valuable resource for the rigorous design and analysis of complex nanophotonic scattering systems.

Here is what makes HELIOS stand out:

- Multiple Environments: It simulates electromagnetic scattering by nanostructures embedded in homogeneous, stratified, or periodic backgrounds.

- Robust Formulation: The software implements the Poggio-Miller-Chang-Harrington-Wu-Tsai (PMCHWT) formulation, utilizing Rao-Wilton-Glisson (RWG) functions on triangular meshes, which is highly reliable for solving scattering problems with penetrable objects.

- Periodic Structures: For 2D lattices like photonic crystals and metasurfaces, the code applies Ewald's transformation to efficiently evaluate the periodic Green's tensor.

- Layered Media: It tackles stratified media using a matrix-friendly formulation and accelerates the computation of Sommerfeld integrals through a smart tabulation-interpolation scheme.

- Comprehensive Outputs: The program calculates crucial optical quantities, including scattering, absorption, and extinction cross-sections, as well as reflectance, transmittance, and near-field distributions.

- Accessible Architecture: HELIOS features a 𝐂++ core for intensive computational operations, seamlessly managed by a Python interface for simulation setup, execution, and post-processing. Additionally, HELIOS provides a user-friendly GUI and detailed documentation about its installation, usage and all its scripts.

Whether you are modeling isolated scatterers, infinite periodic structures, or complex multilayer environments, HELIOS offers a single framework to handle it all! The code is open-source and available on <a href="https://github.com/mavrikak/Helios">GitHub</a>.

Check out the full arXiv <a href="https://doi.org/10.48550/arXiv.2602.23097">preprint</a> to see the detailed formulations and validation examples!

#Nanophotonics #ComputationalElectromagnetics #IntegralEquations #OpenSource #HELIOS #EPFL #NAM #Optics #LightScattering #Simulation #Physics #Research