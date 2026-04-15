---
title: "HELIOS: A surface integral equation software for light scattering in homogeneous, periodic, and stratified environments"
collection: publications
category: manuscripts
permalink: /publication/2026-02-26-HELIOS_arXiv
excerpt: 'Authors: P. S. Mavrikakis, and O. J. F. Martin'
date: 2026-02-26
venue: 'arXiv'
paperurl: 'https://doi.org/10.48550/arXiv.2602.23097'
bibtexurl: 'https://mavrikak.github.io/files/2026-02-26-HELIOS_arXiv.bib'
citation: 'P. S. Mavrikakis and O. J. F. Martin, “HELIOS: A surface integral equation software for light scattering in homogeneous, periodic, and stratified environments,” Feb. 2026, arXiv:2602.23097.'
---
We present HELIOS (HomogEneous and Layered medIa Optical Scattering), an open-source surface integral equation (SIE) software designed for modeling light scattering by particles embedded in homogeneous or layered media and periodic backgrounds. The code implements the Poggio-Miller-Chang-Harrington-Wu-Tsai (PMCHWT) formula- tion that has demonstrated exceptional reliability in solving scattering problems with penetrable objects. Domain boundaries are discretized using triangular meshes, upon which the electric and magnetic surface current densities are expanded using the Rao-Wilton-Glisson (RWG) basis functions. For periodic structures, such as photonic crystals and metasurfaces, HELIOS employs Ewald’s transformation to efficiently evaluate the infinite series associated with 2D lattices. Regarding stratified media, the code utilizes a matrix-friendly approach for the layered media Green’s tensor, computing Sommerfeld integrals and accelerating calculations through a tabulation-interpolation scheme. The source code is implemented in C++, while a Python interface manages the workflow, including simulation setup, solver run, and post-processing. The accuracy and versatility of HELIOS are demonstrated through various examples that cover all its functionalities.