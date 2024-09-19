---
title: "Fitting the Time-of-Flight (ToF) of Quasi-2D Ultracold Yb Atoms"
excerpt: "Under the guidance of Prof. Gyu-Boong Jo, I developed fitting scripts to determine the sample's temperature and chemical potential. By employing the Hartree-Fock (HF) method, we iteratively calculated the occupation distribution of interacting atoms, enabling the computation of their spatial distribution. The theoretical results were then compared and fitted against experimental data to enhance our understanding of the sample's properties.
 <br/><img src='/images/ultracoldatom/ultratitle.png'>"
collection: portfolio
---
In this project, I applied the Hartree-Fock method to iteratively calculate the occupation distribution of interacting atoms in the z-direction eigenlevels at finite temperature $$T$$ and chemical potential $$\mu$$. Subsequently, I computed the theoretical spatial distribution of the gases after Time-of-Flight (ToF), accounting for finite time effects by integrating over the initial positions.

The following figure presents the results:

1. Spatial distribution after ToF (left).
2. Iteration results of interacting particle density compared to the non-interacting case (right).

<br/><img src='/images/ultracoldatom/distributeiteration_theory.png'>

From these figures, it is evident that the initial spatial distribution shaped by the box trap is preserved after ToF. Interactions among atoms lead to noticeable changes in occupation numbers, highlighting the importance of interactions in the system.

Further analysis involved fitting the theoretical calculations to the experimental data. Due to experimental setup limitations that only allowed side images (x-z distributions), we adapted our theoretical (x-y) calculations by integrating them along the z-direction to match the x-distributions. Here are the experimental data and the fitting results:

<br/><img src='/images/ultracoldatom/fit.png'>

We averaged 30 optical density measurements of the samples to obtain a consistent density distribution. The data was fitted using the entire dataset (upper right) and its derivative (lower right). This approach was crucial as it allowed us to separate the contributions from the condensed phase, which are not accounted for in the Bose-Einstein distribution, thereby determining the properties of the thermal part and the proportion of condensation within the sample.
