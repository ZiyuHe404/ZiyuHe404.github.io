---
title: "Analytical and Numerical Study of Photons in Nonlinear Waveguides"
excerpt: "In collaboration with Prof. Xueyue (Sherry) Zhang, I investigated nonlinear waveguides composed of nonlinear coupled cavity arrays. Inspired by previous work, I reproduced calculations of two-photon bound states. Further, I explored utilizing this nonlinear interaction to generate driven-dissipative cat states and investigated the formation of entangled cat states.
 <br/><img src='/images/Nonlinear_wave/titlenonlinear.png'>"
collection: portfolio
---
In this project, we reproduced the results from the [study](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.124.213601) on nonlinear waveguides. Due to discrete translational symmetry, the state in the two-photon subspace can be represented using the Bloch theorem as $$e^{i K r_c}$$ $$\psi_{K}(r^{\prime}) $$, where $$K$$ is the total wavevector, $$r_c$$ is the center-of-mass position, and $$r^{\prime}$$ represents the relative displacement. We calculated the eigenstates and eigenenergies of this system, identifying two-photon bound states.

<br/><img src='/images/Nonlinear_wave/wavefunction_inner.png'>

On the left, we display the two-photon bound state and the two-photon scattering state. On the right, we show the energy band structure in the relative space.

The following image presents the energy spectrum versus the interaction strength $$U$$. Our calculations are in good agreement with the previous work:

<br/><img src='/images/Nonlinear_wave/spectrum.png'>

Further, we explored the wavefunction and the spectrum in the presence of a ZZ interaction. This extended case contains two two-photon bound states with distinct relative wavefunctions:

<br/><img src='/images/Nonlinear_wave/ZZ_interaction.png'>

We calculated the dynamics of this system in the two-photon subspace using QuTiP, as shown below:

<br/><img src='/images/Nonlinear_wave/quantumwalk.png'>

We investigated generating cat states based on this nonlinear interaction. To construct a cat state, we require two bosonic systems or two bosonic modes, $$a$$ and $$b$$, with the following Hamiltonian:

$$
H = -\frac{\chi_aa}{2} a^{\dagger} a^{\dagger} a a + g_2 ( b^{\dagger} a a + a^{\dagger} a^{\dagger} b) + \epsilon_d (b+b^{\dagger})
$$

and two collapse operators:

$$
C_1 = \sqrt{\kappa_a} a,C_2 = \sqrt{\kappa_b} b
$$

The result calculated using QuTiP is shown here:

<br/><img src='/images/Nonlinear_wave/idealcat.png'>

We further extended this study to a cavity side-coupled to a nonlinear waveguide, aiming to generate a flying cat state:

<br/><img src='/images/Nonlinear_wave/flyingcat.png'>

Details documents in [here](/_Research/portfolio-2detail/2ph_bound_state/2ph_bound_state.md).








