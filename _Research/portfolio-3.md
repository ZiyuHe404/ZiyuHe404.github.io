---
title: "Analytical and Numerical Study of Photons in Nonlinear Waveguide"
excerpt: "We started to investigate in nonlinear waveguide which is composed of nonlinear coupled cavity array. Inspired by the previous work, we reproduce their calculations of two photons bound state. Further, we aimed to utilize this nonlinear interaction to generate driven-disspasive cat state and further explored entangled cat state.
 <br/><img src='/images/quantum_pulse/pulse_title.png'>"
collection: portfolio
---
In this project, we reproduced the [work](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.124.213601) in nonlinear waveguide. Given the discrete translational symmetry, the state in two photon subspace can be represented as $$e^{i K r_c}$$ $$\psi_{K}(r^{\prime}) $$ using Bloch theorem. Here, $$K$$ is the total wavevector, $$r_c$$ and $$r^{\prime}$$ represents the center of mass position and the relative displacement. We calculated the eigenstate and eigenenergy of this system, identifying a two photon bound state. The figure below shows the relative wavefunction $$\psi_{K}(r^{\prime})$$ and the eigenenergy at certain $$K$$.

<br/><img src='/images/Nonlinear_wave/wavefunction_inner.png'>

Here, we show the two photon bound state and two photon scattering state at the left, and the band of relative space at the right.

The following is the energy spectrum versus interaction U. Our calculations matched with the previous work.

<br/><img src='/images/Nonlinear_wave/spectrum.png'>

Further, we explored the wavefunction and the spectrum where there existed a ZZ interaction. This extended case contained two two-photon bound states having distinct relative wavefunction.

<br/><img src='/images/Nonlinear_wave/ZZ_interaction.png'>

We explored generating cat state based on this nonlinear interaction. In order to contruct a cat state, we actually need two bosonic systems, or two bosonic modes a and b. It has the following Hamiltonian,
$$
H = -\frac{\chi_aa}{2} a^{\dagger} a^{\dagger} a a + g_2 ( b^{\dagger} a a + a^{\dagger} a^{\dagger} b) + \epsilon_d (b+b^{\dagger})
$$
with two collapse operators,
$$
C_1 = \sqrt{\kappa_a} a,C_2 = \sqrt{\kappa_b} b
$$

The result calculated using QuTiP shows here

<br/><img src='/images/Nonlinear_wave/idealcat.png'>








