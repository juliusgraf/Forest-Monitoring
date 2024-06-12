# Forest Monitoring

## Overview of the project
We implemented the "Collapsed Gibbs sampling for Neyman-Scott processes with gamma weights" algorithm as formulated by Wang et al. (2023) in the context of spatial clustering with anisotropic Gaussian impulse responses. This involved deriving theoretical expressions for evidence, posterior, and prediction probability distributions, and engineering a novel evaluation metric, $\pi_\sigma$. Furthermore, we developed a standardized Python implementation for generating Neyman-Scott processes with anisotropic Gaussian impulse responses, which was previously only available in Julia. This repository contains the associated code and the slides from our final presentation.

## Acknowledgements
This project was conducted at MICS CentraleSupélec (Université Paris-Saclay), within the Pôle Projet P15 - Modélisation mathématique des systèmes complexes. The project team included Teddy Tonin, Ylias Larbi, Ghaith Harzalli, and Maxsuel Fernandes de Almeida, under the supervision of Konstantinos Florakis.

## References
Wang, Y., Degleris, A., Williams, A. H., & Linderman, S. W. (2023). Spatiotemporal Clustering with Neyman-Scott Processes via Connections to Bayesian Nonparametric Mixture Models.
