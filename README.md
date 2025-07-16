# Designing AI-Generated Antimicrobials for Targeting Bacterial Microdomains

## Overview
This repository hosts the supplementary materials for our study on the selective binding of antimicrobial agents to bacterial membranes with distinct mechanical properties. Our work investigates how cardiolipin-rich microdomains—characterized by unique rigidity and altered lipid packing—affect antimicrobial binding and translocation energies, thus informing the rational design of targeted antimicrobial compounds.

## Abstract
> Bacterial membranes are essential for processes such as nutrient transport, signal transduction, and maintaining cellular
integrity. Within these membranes, specialized microdomains , like cardiolipin-rich domains, serve as key sites for protein
localization, membrane curvature regulation, and stress response. These microdomains possess high anionic headgroup
density and specific lipid composition, which can enhance electrostatic and hydrophobic interactions with antimicrobial agents.
In this study, we investigated whether antimicrobial compounds can selectively target membranes with distinct lateral lipid
distributions. To this end, we modeled two bacterial membrane systems: one with a randomized lipid composition and
another featuring an idealized cardiolipin-rich microdomain. Using a generative neural network framework guided by specific
molecular design criteria, we generated AI-driven antimicrobial candidates and assessed their membrane interactions via
free-energy calculations. Our analysis revealed preferential binding of compounds to cardiolipin-rich domains, evidenced by
lower binding energies, alongside higher translocation barriers in these regions, attributable to strong electrostatic anchoring
and tight lipid packing. Further clustering and feature importance analysis identified recurring structural motifs associated with
potent antimicrobial activity, supporting that cardiolipin-rich regions may facilitate selective binding. Parallel toxicity predictions
indicated several top candidates have low predicted toxicity, a critical factor for drug development. Notably, the top AI-designed
compounds were benchmarked against established membrane-targeting drugs to assess similarities in their antimicrobial
activity profiles. By integrating generative AI with advanced membrane modeling, this work establishes a robust framework
for the rational design of new membrane-targeting antimicrobials and highlights how membrane composition influences
drug–membrane interactions and efficacy.

## Repository Contents
- **Raw Energy Files**  
  Contains the primary simulation output data for both raft and non-raft systems. The files are organized into correspondingly named folders.
  
- **Membrane Visualizations**  
  Example representations of the simulated membranes are provided for quick reference
  
- **Diptool Simulation Results**  
  Compiled output files with detailed information derived from Diptool simulations, which summarize energy profiles and binding characteristics.
  
- **Molecular Descriptors**  
  A collection of molecules with comprehensive descriptor annotations
  
  
## Reference
  
 Mateusz Rzycki*, Adam Gruda, *Designing AI-Generated Antimicrobials for Targeting Bacterial Microdomains*, 2025

