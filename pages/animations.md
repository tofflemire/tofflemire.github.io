---
layout: page-fullwidth
title: "Animations"
subheadline: ""
meta_teaser: ""
teaser: "Simulators aren't the only ones who can make cool animations...right?"
categories:
permalink: "/animations/"
---
<!--more-->
<hr>
## TWA 3A
<iframe width="560" height="315" src="https://www.youtube.com/embed/iGKtvyx1_Ss" style="padding:10px;border:10px solid white;" align="left" frameborder="100" allowfullscreen></iframe>

An animation of the mass accretion rate onto the binary system TWA 3A as a function of orbital phase. 

TWA 3A is a young binary star system that is actively accreting material from a protoplanetary disk that surrounds the two stars. Hydrodynamic simulations of the binary-disk interaction predict bursts of accretion near each periastron passage (the closest approach of the two stars in their orbit). TWA 3A has an orbital period of 34.9 days and an eccentricity of 0.63.

The left panel displays the accretion rate as a function of an arbitrarily labeled orbital cycle number. Dashed vertical lines mark TWA 3A's periastron passage. 

The right panel displays a scale schematic of TWA 3A's orbit as the two stars travel through their orbits. 

Mass accretion rates are measured from a photometric excess in the Johnson U-band. Observations were made with the <a href='https://lco.global/' target="_blank">Las Cumbres Observatories</a> 1m telescope network. 

A peer-reviewed article published in the Astrophysical Journal Letters on this result can be found <a href='https://arxiv.org/abs/1706.07073' target="_blank">here</a>.
<hr>
## DQ Tau
<div id="video-wrap">
<iframe width="560" height="315" src="https://www.youtube.com/embed/8HZ36mJSF10" align="left" style="padding:10px;border:10px solid white;" frameborder="100" allowfullscreen></iframe></div>

An animation of the mass accretion rate onto DQ Tau as a function of orbital phase. 

DQ Tau is a young binary star system that is actively accreting material from its protoplanetary disk. Hydrodynamic simulations of the binary-disk interaction predict bursts of accretion near each periastron passage (the closest approach of the two stars in their orbit). DQ Tau has an orbital period of 15.8 days and an eccentricity of 0.57.

The left panel displays the accretion rate as a function of an arbitrarily labeled orbital cycle number. Dashed vertical lines mark DQ Tau's periastron passage. 

The right panel displays a scale schematic of DQ Tau's orbit as the two stars travel through their orbits. 

Mass accretion rates are measured from a photometric excess in the Johnson U-band. Observations were made with the <a href='https://lco.global/' target="_blank">Las Cumbres Observatories</a> 1m telescope network, the <a href='http://www.apo.nmsu.edu/Telescopes/ARCSAT/index.html' target="_blank">Apache Point Observatory's ARCSAT</a> telescope, and the <a href='https://www.noao.edu/0.9m/' target="_blank">WIYN 0.9m</a> telescope.

A peer-reviewed article published in the Astrophysical Journal on this result can be found <a href='https://arxiv.org/abs/1612.02431' target="_blank"> here</a>.
<hr>
## Star Spots -- Doppler Imaging Demo
<div id="video-wrap">
<iframe width="560" height="315" src="https://www.youtube.com/embed/UbxJOw3MoUo" align="left" style="padding:10px;border:10px solid white;" frameborder="100" allowfullscreen></iframe></div>

I am interested in star spots and their effects on light curves and stellar line profiles. I spent some simulating these effect that resulted in this animation. 

An animation of the integrated flux and emergent line profile from a spotted star as a function of rotational phase. In this example, the star is viewed at an inclination of 45 degrees and has an equatorial rotational velocity of 150 km/s. As the spot rotates onto the projected surface, it dims the star and alters the line profile. 

Top Left: The star's normalized surface brightness. A linear limb-darkening is applied using 0.75 as the limb darkening coefficient (appropriate for low-mass stars). Lines of constant longitude and latitude are over plotted; bold lines mark the equator and meridian. The spot is located at a latitude of 30 degrees, a longitude of 30 degrees, and has 20% the brightness of the underlying surface. 

Top Right: The integrated flux from the star as a function of rotational phase. The grey dashed line is the full light curve, the blue dot represents the current location in rotational phase and brightness relative to an unspotted surface. 

Bottom Left: The projected radial velocity of each surface element. Solid body rotation is assumed. 

Bottom Right: Integrated line profile. Each individual surface element is represented with a gaussian of 5 km/s at a spectral resolution of R~50,000. Each individual profile is shifted by the projected radial velocity (Bottom Left) and normalized by the surface brightness (Top Left). The summed result is a rotationally broadened absorption line profile with additional features when the spot is present. The dashed black line is an analytic curve for pure rotational broadening. Vertical dashed grey lines are the v sini values. A nice description of why a dark spot makes an upward bump in the line profile can 
be found <a href="https://articles.adsabs.harvard.edu/pdf/1983PASP...95..565V" target="_blank">here</a>.


This animation was made in python with the following packages: matplotlib, moviepy, scipy, numpy.
<hr>
More animations I have made for grad classes over the years can be found on my <a href='https://www.youtube.com/user/BenTofflemire' target="_blank">youtube channel</a>. 



