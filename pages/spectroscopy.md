---
layout: page
title: "Time-Series Spectroscopy of Accreting Pre-MS Binary Stars"
subheadline: ""
meta_teaser: ""
teaser: ""
categories:
permalink: "/spectroscopy/"
---
<a href='https://tofflemire.github.io/research/'>(A more general overview of my thesis can be found here.)</a>
<hr>

## Motivation
Our effort to observationally characterize the binary-disk interaction with time-series, optical and near-infrared photometry (more about that <a href='https://tofflemire.github.io/photometry/'>here</a>) has allowed us to make critical tests of binary accretion theory. This method, however, only provides course information such as the combined accretion rate onto both stars and the relative temperature and amount of circumstellar dust near the stars. Most importantly, these data do not supply kinematic information on the accretion streams that bridge the gap between the central binary and the circumbinary disk. 

The prediction of periodic pulsed accretion events, which our photometry supports, has become a consensus of many diffferent numerical simulations. One prediction that sets different simulations apart, however, is which star will preferentially accrete the mass from the circumbinary streams. Some modeling efforts suggest that mass will preferentially feed the primary or secondary depending on the orbital parameters. Others suggest the disk itself plays a significant role in determining the primary accretor. The figure below from <a href='http://adsabs.harvard.edu/abs/2016ApJ...827...43M' target='blank'>Munoz & Lai 2016</a> presents the accretion rate for an equal-mass binary with an eccenticity of 0.5. Each star's accretion rate is presented in the red and blue curves. The star represented with the blue curve is clearly the dominant accretor in the system, however, these author argue this has more to do with the properties of the disk than the binary. 

<a href='http://adsabs.harvard.edu/abs/2016ApJ...827...43M' target='blank'>
  <img src="/local_files/ML2016_Mdot.jpg" width="700" ALIGN="left">
</a>

In these simulations the circumbinary disk develops an asymmetry that precess over the course of hunderds of binary orbits. The star who's apastron passage brings it nearest to the overdense region will preferentially receive more mass. During the time frame plotted above it is the star depicted in blue, but over many binary orbital periods, the star depicted in the red curve will become the dominant accretor (see Figure 3 in <a href='http://adsabs.harvard.edu/abs/2016ApJ...827...43M' target='blank'>Munoz & Lai 2016</a>). 

The above discussion is just one explaination of the physics that could be behind determining which star is the dominant accretor in a binary systems. But it exemplifies the types of detailed inferences that can be made about the binary-disk interaction and inner disk dynamics generally with information kinematics of accretion flows. 

## Time-Series Spectroscopy
For a subset of the binaries in our photometric sample we have obtained time-series, high-resolution, optical spectroscopy. These observations allow us to begin to probe the kinematic properties of binary-disk interaction. It was crucial that these observations overlap with our more densely sampled photometric coverage to provide context with the large-scale accretion trends in the systems. 

Our spectra come from the <a href='https://www.salt.ac.za/' target='blank'>SALT</a> telescope's High-Resolution Spectrograph (HRS) and the <a href='http://www.astro.yale.edu/smarts/' target='blank'>SMARTS</a> 1.5m CHIRON spectrograph. Both are echelle spectrographs providing spectral resolutions of R~30,000 and wavelength coverage from ~3300-9000&#8491;.

### Early Results - TWA 3A
TWA 3A is a near-equal-mass (q=0.84), pre-MS binary with an eccentricity of 0.63 and an orbital period of 34.9 days. Over the course of 3 consecuative orbital periods we were able to obtain 14 SALT/HRS measurements. 

The figure below presents the accretion tracing emission line H-alpha. Observations are ordered according to their orbital phase listed in the top right of each panel; the color-coding and number in parenthesis designates the orbit in which the observation was made. Following the conclusion made from <i>U</i>-band observations (also tracing the accretion rate), the H-alpha emission increases near periastron passage, just as models would predict for an eccentric binary. The vertical blue and red lines at the bottom of each plot mark the primary and secondary stellar velocity, respectively. Due to H-alpha's large and complex emission profile it is difficult to perscribe emission to one star over another, but structure in it's high-velocity wings may be able to trace emission in accretion stream further from the stars. 
<img src="/local_files/Ha_all.png" width="700" ALIGN="left">

<br> 

<img src="/local_files/TWA_HeI.png" width="300" ALIGN="left">
The figure at the left presents the accretion tracing emission line He I 5876&#8491;. As with the plot above, the spectra are ordered by their orbital phase and color coded by the orbit in which they were obtained. Both are presented as text to the right of each line. Blue and red vertical lines associated with each spectrum mark the primary and secondary stellar velocities, respectively. Due to its relatively narrow width, we can use He I to trace which star is the dominant source of accretion emission. The He I velocity centroid consistently coincides with the primary velocity suggesting it is the primary accretor. 

A paper on our TWA 3A spectra is in preparation but a conference proceedings with our preliminary results can be found <a href='/local_files/tofflemire_sfst.pdf' target='blank'>here</a>.

### Ongoing Work
With almost 6000&#8491; of high-resolution wavelength coverage, there are many features to investigate across our temporal observing sequence. We are currently exploring the rest of this rich data set. 

<hr>

## SALT/HRS Reductions
As a new instrument, HRS does not have a fully developed, publically available reduction pipeline. There are a few aspects of the instrument that make an optimal spectral extraction not straightforward. This <a href='https://tofflemire.github.io/spectroscopy/hrs_red/'>page</a> chronicals my reduction scheme for HRS data. 
