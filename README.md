# pr-sentation-regression-minority-report

**Definition 1.1 (Standard Model Lagrangian).** Let $\mathcal{L}_{\text{SM}}$ denote the Lagrangian density of the Standard Model. This compact mathematical formulation describes the fundamental interactions between elementary particles ([... taken from home.cern](https://home.cern/news/news/cern/sit-down-coffee-standard-model)). The functional form of $\mathcal{L}_{\text{SM}}$ is partitioned into four distinct, gauge-invariant components that govern the kinematics and dynamics of the system:

* The **Gauge Bosons** term dictates the kinematics and self-interactions of the force-mediating vector fields (gluons, $W$/$Z$ bosons, and photons).
* The **Fermion Dynamics** term describes the kinetic energy and gauge interactions of the spin-1/2 quarks and leptons.
* The **Higgs Mechanism** encompasses the scalar field potential responsible for spontaneous electroweak symmetry breaking.
* The **Yukawa Couplings** define the interaction between the scalar Higgs field and chiral fermions, thereby dynamically generating fermion masses.

Accordingly, the complete Lagrangian density is expressed as:

$$
\mathcal{L}_{\text{SM}} = \underbrace{-\frac{1}{4} G_{\mu\nu}^A G^{A\mu\nu} - \frac{1}{4} W_{\mu\nu}^a W^{a\mu\nu} - \frac{1}{4} B_{\mu\nu} B^{\mu\nu}}_{\text{Gauge Bosons}} + \underbrace{\sum_{f} \bar{\psi}_f i \gamma^\mu D_\mu \psi_f}_{\text{Fermion Dynamics}} + \underbrace{(D_\mu \Phi)^\dagger (D^\mu \Phi) - \mu^2 \Phi^\dagger \Phi - \lambda (\Phi^\dagger \Phi)^2}_{\text{Higgs Mechanism}} - \underbrace{\sum_{i,j=1}^3 \left( Y_{ij}^e \bar{L}_L^i \Phi e_R^j + Y_{ij}^u \bar{Q}_L^i \tilde{\Phi} u_R^j + Y_{ij}^d \bar{Q}_L^i \Phi d_R^j + \text{h.c.} \right)}_{\text{Yukawa Couplings}}
$$
