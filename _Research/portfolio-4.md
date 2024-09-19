---
title: "Fitting the ToF of the 2D Yb Ultracold Atom"
excerpt: "Under the guidance of Prof. Gyu-Boong Jo, I developed a fitting scipts to determine the samples's temperature and chemical potential. Using the HF method to iteratively calculate the occupation, we finally get the spatial distribution of atoms theoraticaly. The theoratical result can be compared to the experimental data, further be fitted to acquire the samples' property.
 <br/><img src='/images/quantum_pulse/pulse_title.png'>"
collection: portfolio
---

First, I utilized the HF method to iteratively calculate the occupation distribution of interacting atoms. Second, I computed the theoretical spatial distribution of the gases after Time of Flight (ToF), accounting for the infinite time effect by integrating over initial positions. The following is the result.1.the spatial distribution after ToF(left). 2. the iteration results of interacting particle density compared to non-interacting case(right).

<br/><img src='/images/ultracoldatom/distributeiteration_theory.png'>

from the figure, we can see that the distribution preserve the trace of intial spatial distribution (box trap). the interaction between the atoms can lead to a change in occupation.

Further, we can use this theoratical calculation to fit the experimental data. Due to some setup limitation, we can only take a sideimage of the samples, indicating the data is the x-z distributions. But our theoratical calculation is x-y distribution. Therefore, we integrate them to x distribution. Here is the experimental data and the fitting result.

<br/><img src='/images/ultracoldatom/fit.png'>

Here, we average 30 optical density measurement of the samples and get the density distribution of the sample. We fit the measurement using the whole data(upperright) and its swing(lowerright). The reason for fitting the swing is there is a proportion of atoms in condensation, which is not included in the BE distribution. Therefore we fit the swing of the data to acqure the property of the thermal part and determine the condesatoin proportion from the rest. 