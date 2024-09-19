---
title: "Fitting the ToF of the quasi 2D Yb Ultracold Atom"
excerpt: "Under the guidance of Prof. Gyu-Boong Jo, I developed fitting scripts to measure the sample's temperature and chemical potential. By employing the Hartree-Fock (HF) method, we iteratively calculated the occupation distribution of interacting atoms, enabling us to calculate the spatial distribution of these atoms. The theoretical results were then compared and fitted against experimental data to further refine our understanding of the sample's properties.
 <br/><img src='/images/quantum_pulse/pulse_title.png'>"
collection: portfolio
---

Initially, I applied the HF method to calculate the occupation distribution of interacting atoms iteratively. Subsequently, I computed the theoretical spatial distribution of the gases after Time of Flight (ToF), considering the finite time effect through integration over initial positions. 
The following is the result.1.the spatial distribution after ToF(left). 2. the iteration results of interacting particle density compared to non-interacting case(right).

<br/><img src='/images/ultracoldatom/distributeiteration_theory.png'>

From the figures, it is evident that the initial spatial distribution shaped by the box trap is preserved. Interactions among atoms lead to noticeable changes in occupation, highlighting importance of interaction.

Further analysis involved fitting the theoretical calculations to the experimental data. Due to experimental setup limitations that only allowed side images (x-z distributions), we had to adapt our theoretical (x-y) calculations by integrating them to match the x-distributions. Here are the experimental data and the fitting results:

<br/><img src='/images/ultracoldatom/fit.png'>

We averaged 30 optical density measurements of the samples to obtain a consistent density distribution. The data was fitted using the entire dataset (upper right) and its swing (lower right). This approach was crucial as it allowed us to separate the contributions from the condensed phase, which are not accounted for in the Bose-Einstein distribution, and thereby determine the properties of the thermal part and the proportion of condensation within the sample.
