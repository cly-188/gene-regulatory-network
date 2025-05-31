# gene-regulatory-network
# Topological Structure and Dynamics of Biomolecular Networks

The topological structure of biomolecular networks, such as regulatory pathways and feedback loops, determines their dynamics and bifurcation behaviors. Understanding the relationship between network topology and system dynamics remains a central challenge in systems biology. This study analyzes a framework based on Jacobian matrix decomposition, which systematically links network topology to the stability and bifurcation of equilibrium points and limit cycles.

## Tristable Model of Early T-Cell Development

We first examined a tristable model of early T-cell development, where saddle-node bifurcations govern transitions between cellular states. By decomposing the Jacobian matrix into submatrices corresponding to distinct feedback loops, we identified critical subnetworks—particularly the indirect feedback loop involving GATA3—that dominate bifurcation behavior near transition points. This approach:

- Quantifies the contribution of local topology to global dynamics
- Reveals how perturbations propagate through specific network structures

## Extended Analysis of the p53-Mdm2 Network

The key innovation of this study lies in its extended analysis of the p53-Mdm2 network. Applying a similar methodology to oscillatory systems, we investigated:

1. Dynamic properties of negative feedback loops under noisy conditions
2. Frequency-locking phenomena in biological oscillations

Using the p53-Mdm2 regulatory network as a case study, we:

- Constructed Poincaré maps
- Analyzed limit cycle stability
- Demonstrated that when the frequency of periodic noise forms a rational ratio with the intrinsic frequency of the limit cycle, the oscillation frequency locks onto:
  - The noise frequency, or
  - Its subharmonics

This provides a theoretical explanation for experimentally observed "frequency-locking" phenomena.

## Conclusions and Future Directions

By integrating nonlinear dynamics with network theory, this work offers novel methodological tools for:

- Analyzing complex biological systems
- Controlling system behaviors

Future research may extend this framework to:

- Multicellular systems
- Metabolic networks
- Other higher-order scenarios

This approach has potential to advance:
- Quantitative biology
- Precision medicine
