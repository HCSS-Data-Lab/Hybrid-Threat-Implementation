# Hybrid-Threat-Implementation
This repository contains the code for constructing the input probability distributions for the hybrid threat scenario. It also contains the causal influence diagram approach to compute the optimal counter-hybrid measure per scenario as well as the multi-agent influence diagram approach to compute equilibria under strategic contestation. Finally, this repository contains the sensitivity analyses conducted to gauge individual parameter contributions to the model output. 

## Construction of the Parameters and Modeling Approaches
The Notebook Game_Theoretic_Approach_Hybrid_Deterrence contains the construction of the distributions, which are sampled from to construct 1000 experiments. Both the causal influence diagram simulations, as well as the multi-agent influence diagram simulations, are included in this notebook. It also contains some visualizations of the results.

## Sensitivity Analysis
The Global Sensitivity Analysis Reporting tool of Stein et al. (2022) is used to conduct the sensitivity analyses. Full reports are available in the folder *Sensitivity Analyses*. For details on the tool, we refer to the original repository https://github.com/nikivanstein/GSAreport, while specifics about the reported values can be found in the original paper: https://ieeexplore.ieee.org/abstract/document/9903639. To open the sensitivity reports, the entire repository should be cloned first.


