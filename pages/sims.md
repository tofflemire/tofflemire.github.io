---
layout: page-fullwidth
title: "Hydrodynamics Simulations of Binary Accretion"
subheadline: "(In Progress)"
meta_teaser: ""
teaser: ""
categories:
permalink: "/sims/"
---
<a href='https://tofflemire.github.io/binary_accretion/'>(A more general overview of my thesis can be found here.)</a>
<hr>

## Motivation
Short-period, pre-MS binary stars pose a challenge to current simulations of the binary-disk interaction. Due to their small separation at periastron passage (tens of stellar radii) there exists a close match between the inner magnetic truncation radius assumed for single stars and the outer truncation radius imposed by binary orbital dynamics. Without including the disruptive effect stellar magnetic fields have on disk material, current simulations do not accurately describe the binaries in our sample. 

<img src="/local_files/Model_mag.png" width="300" ALIGN="left" HSPACE="25" /> 
The figure to the right illustrates the scales of the important dynamic and magnetic processes at play. The background image is a hydrodynamic simulation of binary accretion by <a href='http://adsabs.harvard.edu/abs/2016ApJ...827...43M' target='blank'>Munoz & Lai 2016</a> for an equal-mass binary with an eccentricity of 0.5. This snap shot comes from the simulation's periastron passage. If we assume DQ Tau's orbital parameters (periastron separation of ~12 stellar radii), the dashed circles mark the magnetospheric truncation radii assumed for single stars. At this scale, the entire circumstellar disk falls within a region where magnetic fields are predicted to disrupt stable disk material. This has implications for the timing and variability of the pulsed accretion events predicted by the binary-disk interaction, potentially explaining the discrepancies between these models and our observations (more on that <a href='https://tofflemire.github.io/photometry/'>here</a>).

## Tailored Numerical Simulations with AREPO
To create simulations that are more representative of the short-period accreting binaries in our sample, we have initiated a collaboration with Diego Munoz to run a new set of simulations tailored to DQ Tau and TWA 3A. The simulations will have similar properties as those in <a href='http://adsabs.harvard.edu/abs/2016ApJ...827...43M' target='blank'>Munoz & Lai 2016</a> but we will vary specific properties such as the inner accretion radius for each star (mimicking the effects of magnetic fields) and the disk viscosity. Simulation will be run with the adaptive mesh refinement hydrodynamic code, AREPO. This project is just getting underway but I’m excited about the prospect of comparing these custom simulations to our observations.


