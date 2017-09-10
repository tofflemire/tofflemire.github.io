---
layout: page
title: "Time-Series Photometry of Accreting Pre-MS Binary Stars"
subheadline: ""
meta_teaser: ""
teaser: ""
categories:
permalink: "/photometry/"
---
<a href='https://tofflemire.github.io/research/'>(A more general overview of my thesis can be found here.)</a>
<hr>

## Motivation
Numerical simulations of the binary-disk interaction predict that the accretion rate onto the stellar surface(s) will be modulated by the binary orbital period. Orbital dynamics influence the flows of circumbinary and circumstellar material that, depending on the binary orbital parameters, can lead to periodic enhanced accretion events. The animation below is a simulation of the binary-disk interaction for an equal-mass binary with an eccentricity of 0.5. The simulation comes <a href='http://adsabs.harvard.edu/abs/2016ApJ...827...43M' target='blank'>Munoz & Lai 2016</a>. The color scheme present the logarithmic surface density with high densities in while and low densities in black. 

<video src="/local_files/movie_e05.mp4" width="400" height="400" ALIGN="left" controls preload></video>

In a simplistic summary, the binary orbit clears out a central gap creating a circumbinary disk and a circumstellar disk around each star. As this eccentric binary goes through its orbit, apastron passage (furthest separation of the two stars) induces a stream of material, made from the inner edge of the circumbinary disk, that brings material into the cleared gap, feeding the circumstellar disks. The figure below presents the mass accretion rate from this simulation where bursts of accretion are seen proceeding each periastron passage (closest approach of the two stars). 

<a href='http://adsabs.harvard.edu/abs/2016ApJ...827...43M' target='blank'>
  <img src="/local_files/ML2016_Mdot.jpg" width="700" ALIGN="left">
</a>

The predicted time-variable accretion is most extreme for eccentric, equal-mass binaries. The specific phase, duration, and amplitude of periodic enhanced accretion events depend sensitively on the binary orbital parameters. If the behavior depicted by these models are accurate, they carry many implications for the formation of stars and planets in the binary environment. However, conclusive observational evidence for this binary accretion paradigm has yet to be made.

## Survey of Accretion Variability in Pre-MS Binaries

To test the predictions of the binary-disk interaction, we have conducted a long-term photometric monitoring campaign capable of tracing the time-variable accretion behavior of short-period, pre-MS binaries. We have compiled a sample of nine shirt-period binaries with diverse orbital parameters allowing us to not only search for evidence of periodic enhanced accretion events but also test their orbital parameter dependence. 

With the Las Cumbres Observatory (<a href='https://lco.global/' target='blank'>LCO</a>) global telescope network, we are able to observe our binaries at candences and over time periods that previously could not have been done from a single observing site. For each binary we created a custom observing program that provided 20 observations per orbit for 10 consecuative orbital periods. Our observations were taken in broadband <i> UBVRIY </i> and narrowband H-alpha and H-beta filters. Most crutial for our work is the inclusion of <i>U</i>-band which can be used to determine the accretion rate. 

<!-- <a href='https://lco.global/' target='blank'> <img src="/local_files/LCO-logo-web.jpg" width="200" ALIGN="left"> </a> -->

At the same time, we had queue scheduled observations with the <a href='http://www.astro.yale.edu/smarts/' target='blank'>SMARTS</a> 1.3m telescope taking <i>BV</i> and <i>JK</i> images for a subset of our binary sample. The optical data provide an indirect measure of the accretion luminosity while the near-infrared trace the amount and temperature of circumstellar dust. 

<!-- <a href='http://www.astro.yale.edu/smarts/' target='blank'> <img src="/local_files/smarts.jpg" width="300" ALIGN="right"> </a> -->

## Early Results

With our observations now complete, we have focused on the eccentric binaries in our sample, DQ Tau and TWA 3A, where the level of accretion variability is predicted to be highest. 

### DQ Tau
DQ Tau is an equal-mass, pre-MS binary with an eccentricity of 0.57 and an orbital period of 15.8 days.

<img src="/local_files/DQ_Mdot.png" width="400" ALIGN="right" HSPACE="25" />
The figure to the right presents the mass accretion rate as a function of orbital cycle. The mass accretion rate is derived from LCO <i>U</i>-band observations. The vertical dashed lines mark periastron passages. Although there is a significant amount of variation from one orbit to the next, we find consistent accretion events near periastron passages, just as the models above predict. A fourier analysis of these data find periodicity in the accretion rate matching the oribtal period. 

<img src="/local_files/DQ_Model.jpg" width="400" ALIGN="left" HSPACE="25" />
To more readily compare our observations to the results of numerical simulations, we have derived the median accretion rate as a function of orbital phase. The figure on the left presents DQ Tau's median accretion rate in blue and the results on the <a href='http://adsabs.harvard.edu/abs/2016ApJ...827...43M' target='blank'>Munoz & Lai 2016</a> simulation in red. Good agreement exists in that both are periodic and have similar average durations, providing strong evidence for accretion stream-fed accretion events.

The differences between the two, most notably the phase shift in the observed accretion events and large amount of variability observed, point to limitation with current modeling efforts. We believe the main source of discrepancy between the models and observations of DQ Tau has to due with the impact stellar magnetic fields have on accretion flows. (No model of binary accretion currently includes stellar magentic fields.) 

Low mass stars have strong magentic fields that are capable of distrupting disk material near the stellar surface. Single stars are typically assumed to have a magnetically dominated region within ~5 stellar radii where magnetic fields confine accretion flows, funneling them onto the star at magnetic footpoints. The orbit of DQ Tau brings the two stars to within ~12 stellar radii of eachother, making it unlikely that each star is able to host a circumstellar disk like the models suggest. Without circumstellar disks (i.e. without a reserviour of material near each star), accretion events become sensitive to the timing at which circumbinary accretion streams supply material to the central stars, delaying accretion events as compared to models. While these models may not be a great match to DQ Tau, they are likely to be more representative of wider binaries where stable circumstellar disks are more likely. 

We are currently investigating the role circumstellar disks play on the timing and variability of binary, pulsed accretion events in collabotation with Diego Munoz. More about that project be found <a href='https://tofflemire.github.io/sims/'>here</a>.

<!-- A little bit about <a href='http://www.apo.nmsu.edu/Telescopes/ARCSAT/index.html' target='blank'>ARCSAT</a> and the <a href='https://www.noao.edu/0.9m/' target='blank'>WIYN 0.9m</a> telescopes. -->

<!-- <img src="/local_files/DQ_CMD.jpg" width="300" ALIGN="left"> --> 

<a href='http://adsabs.harvard.edu/abs/2017ApJ...835....8T' target='blank'> A link to the peer-reviewed paper on DQ Tau can be found here.</a>

An animation of DQ Tau's accretion rate as the stars move through their orbit can be found <a href='https://tofflemire.github.io/animations/'>here</a>.

### TWA 3A
TWA 3A is a near-equal-mass (q=0.84), pre-MS binary with an eccentricity of 0.63 and an orbital period of 34.9 days.

<img src="/local_files/TWA_3A_LC.png" width="700" ALIGN="right" HSPACE="25" />

<img src="/local_files/TWA_Mdot_AveComp_FINAL.png" width="400" ALIGN="left" HSPACE="25" />


An animation of TWA 3A's accretion rate as the stars move through their orbit can be found <a href='https://tofflemire.github.io/animations/'>here</a>.

<a href='http://adsabs.harvard.edu/abs/2017ApJ...842L..12T' target='blank'> A link to the peer-reviewed paper on TWA 3A can be found here.</a>

## Ongoing Work

