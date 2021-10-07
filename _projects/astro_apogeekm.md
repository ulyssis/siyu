---
layout: page
title: APOGEE KM dwarfs
description: measuring metallicities
img: /assets/img/rzww_web.jpg
importance: 5
category: astronomy
---

The metallicities of the smallest stars are particularly difficult to determine due to their faint magnitudes and complicated spectra. These cool dwarfs are some of the most common stars in the galaxy, however, so their abundances are particularly useful both for detailed Galactic chemical evolution models and for understanding the exoplanets orbiting small stars. 

[APOGEE](https://www.sdss.org/surveys/apogee-2/) is a component of the [Sloan Digital Sky Survey](https://www.sdss.org) focused on determining stellar parameters as a probe of our Galaxy's structure and evolution. The APOGEE survey consists mid-resolution infrared spectroscopy fit by a model grid to obtain surface temperatures, gravities, and abundance patterns. APOGEE focuses mostly on giant stars, but has also observed thousands of cool (K and M) dwarfs. 

In 2015, I worked with an initial sample of these KM dwarfs to confirm their catalog parameters, compare stellar models, and look for optimal colors for photometric indicators of metallicity and surface temperature. We found that previous stellar models didn't match the coolest M dwarfs, and we also found strong correlations between SDSS r-z color, WISE W1-W2 color, and these fundamental stellar parameters.

<div class="img_row">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/rzww.png" alt="" title=""/>
</div>
<div class="col three caption" style="float: right">
WISE W1-W2 color as a function of SDSS r-z color shown with colors indicating effective temperatures and metallicities from the SDSS APOGEE ASPCAP catalog. This color combination separates metallicity and temperature in different directions, allowing characterization of both properties using photometry alone. To be included in (Schmidt et al. 2019, in prep.) 
</div>

Since the initial work, the APOGEE data set has doubled and Gaia has released parallaxes for the majority of these nearby stars, and I am working with Jennifer Johnson and Victoria DiTomasso to update and expand the APOGEE KM dwarf project and apply the metallicity indicators to a sample of a million M dwarfs in the Solar neighborhood. Expect new results soon!

#### Related Publications
<div class="publications">
{% bibliography -f papers --query @*[group=apogee]* %}
</div>