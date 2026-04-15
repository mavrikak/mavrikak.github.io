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

𝐄𝐱𝐜𝐢𝐭𝐢𝐧𝐠 𝐧𝐞𝐰𝐬 𝐟𝐨𝐫 𝐭𝐡𝐞 𝐧𝐚𝐧𝐨𝐩𝐡𝐨𝐭𝐨𝐧𝐢𝐜𝐬 𝐚𝐧𝐝 𝐜𝐨𝐦𝐩𝐮𝐭𝐚𝐭𝐢𝐨𝐧𝐚𝐥 𝐞𝐥𝐞𝐜𝐭𝐫𝐨𝐦𝐚𝐠𝐧𝐞𝐭𝐢𝐜𝐬 𝐜𝐨𝐦𝐦𝐮𝐧𝐢𝐭𝐢𝐞𝐬! 🚀

I'm thrilled to share a new arXiv preprint detailing 𝐇𝐄𝐋𝐈𝐎𝐒 (𝐇omog𝐄neous and 𝐋ayered med𝐈a 𝐎ptical 𝐒cattering), a new powerful 𝐨𝐩𝐞𝐧-𝐬𝐨𝐮𝐫𝐜𝐞 𝐬𝐨𝐟𝐭𝐰𝐚𝐫𝐞 𝐟𝐨𝐫 𝐦𝐨𝐝𝐞𝐥𝐢𝐧𝐠 𝐥𝐢𝐠𝐡𝐭 𝐬𝐜𝐚𝐭𝐭𝐞𝐫𝐢𝐧𝐠. Developed by myself, under the supervision of Prof. Olivier J.F. Martin at EPFL's 𝐍𝐚𝐧𝐨𝐩𝐡𝐨𝐭𝐨𝐧𝐢𝐜𝐬 𝐚𝐧𝐝 𝐌𝐞𝐭𝐫𝐨𝐥𝐨𝐠𝐲 𝐋𝐚𝐛𝐨𝐫𝐚𝐭𝐨𝐫𝐲, this tool serves as a valuable resource for the rigorous design and analysis of complex nanophotonic scattering systems.

Here is what makes HELIOS stand out:

• 𝐌𝐮𝐥𝐭𝐢𝐩𝐥𝐞 𝐄𝐧𝐯𝐢𝐫𝐨𝐧𝐦𝐞𝐧𝐭𝐬: It simulates electromagnetic scattering by nanostructures embedded in homogeneous, stratified, or periodic backgrounds.

• 𝐑𝐨𝐛𝐮𝐬𝐭 𝐅𝐨𝐫𝐦𝐮𝐥𝐚𝐭𝐢𝐨𝐧: The software implements the Poggio-Miller-Chang-Harrington-Wu-Tsai (PMCHWT) formulation, utilizing Rao-Wilton-Glisson (RWG) functions on triangular meshes, which is highly reliable for solving scattering problems with penetrable objects.

• 𝐏𝐞𝐫𝐢𝐨𝐝𝐢𝐜 𝐒𝐭𝐫𝐮𝐜𝐭𝐮𝐫𝐞𝐬: For 2D lattices like photonic crystals and metasurfaces, the code applies Ewald's transformation to efficiently evaluate the periodic Green's tensor.

• 𝐋𝐚𝐲𝐞𝐫𝐞𝐝 𝐌𝐞𝐝𝐢𝐚: It tackles stratified media using a matrix-friendly formulation and accelerates the computation of Sommerfeld integrals through a smart tabulation-interpolation scheme.

• 𝐂𝐨𝐦𝐩𝐫𝐞𝐡𝐞𝐧𝐬𝐢𝐯𝐞 𝐎𝐮𝐭𝐩𝐮𝐭𝐬: The program calculates crucial optical quantities, including scattering, absorption, and extinction cross-sections, as well as reflectance, transmittance, and near-field distributions.

• 𝐀𝐜𝐜𝐞𝐬𝐬𝐢𝐛𝐥𝐞 𝐀𝐫𝐜𝐡𝐢𝐭𝐞𝐜𝐭𝐮𝐫𝐞: HELIOS features a 𝐂++ core for intensive computational operations, seamlessly managed by a 𝐏𝐲𝐭𝐡𝐨𝐧 interface for simulation setup, execution, and post-processing. Additionally, HELIOS provides a 𝐮𝐬𝐞𝐫-𝐟𝐫𝐢𝐞𝐧𝐝𝐥𝐲 𝐆𝐔𝐈 and detailed documentation about its installation, usage and all its scripts.

Whether you are modeling isolated scatterers, infinite periodic structures, or complex multilayer environments, HELIOS offers a single framework to handle it all! The code is open-source and available on <a href="https://github.com/mavrikak/Helios">GitHub</a>.

Check out the full arXiv <a href="https://doi.org/10.48550/arXiv.2602.23097">preprint</a> to see the detailed formulations and validation examples!

#Nanophotonics #ComputationalElectromagnetics #IntegralEquations #OpenSource #HELIOS #EPFL #NAM #Optics #LightScattering #Simulation #Physics #Research