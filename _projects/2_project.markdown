---
layout: page
title: H&alpha; emission lines
description: tracing quiescent chromospheres
img: 
---

The H&alpha; emission line is generated in a magnetically heated upper layer of a star's atmosphere called its chromosphere. The presence of H&alpha; indicates that there is a magnetic field at the surface of the star, and it is often used as a magnetic activity indicator because it is the most easily observed tracer of magnetism in the coolest stars and warmest brown dwarfs.

### emission lines in the coolest stars 

One of my projects is to examine the presence of H&alpha; in a large sample of M and L dwarfs observed as part of the Sloan Digital Sky Survey [(SDSS)](https://www.sdss.org/). The emission line traces an unexpected trend - throughout the sequence of M dwarfs, the fraction of stars that have H&alpha; increases until it peaks close to the coolest stars (early-L dwarfs). This indicates that  hot chromospheric emission is more common on cooler stars than on warmer stars. 

This effect is due primarily to the relationship between magnetic activity and age. Young stars have strong magnetic fields, but as they age, the rotation that feeds their magnetic field gradually slows, resulting in weaker magnetic fields for older stars. Warmer stars are efficient at dissipating their magnetic field, so fewer of them are active. The coolest stars remain active for many billions of years, sometimes as long as the current age of the universe. 

<div class="img_row">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/frac_binomial_errs.png" alt="" title="fraction of emission as a function of spectral type"/>
</div>
<div class="col three caption" style="float: right">
The fraction of dwarfs that have H&alpha; emission as a function of spectral type (a tracer of the surface temperature). The fraction of magnetically active dwarfs increases throughout the M spectral sequence, then declines through the L spectral sequence. From <a href='https://ui.adsabs.harvard.edu/abs/2018AJ....155....6M'>Schmidt et al. 2015</a>.
</div>

The fraction of active stars declines for stars cooler than spectral type L0, likely because the atmospheres are cool enough that it is not possible to generate H&alpha; emission. It's also possible that the magnetic fields of warm brown dwarfs are configured differently than those of smalls stars. The exact reason is still an open question in the magnetism of stars and brown dwarfs.  

### H&alpha; line generation

As part of my dissertation, I examined the formation of the H&\alpha; emission line in cool star chromospheres using the [RH](https://ui.adsabs.harvard.edu/abs/2001ApJ...557..389U/abstract) radiative transfer code [(current version available here)](https://rh15d.readthedocs.io/en/latest/). I found that the H&alpha; emission line could be produced on objects with very cool (1700 K) photospheres as long as some chromospheric material was heated to 8000K, and that the weak emission lines observed in the coolest stars were consistent with either less dense emission regions or smaller surface coverage on stars. 

<div class="img_row">
    <img class="col half left" src="{{ site.baseurl }}/assets/img/chr1.jpg" alt="" title="atmospheric temperature structure diagram"/>
    <img class="col half left" src="{{ site.baseurl }}/assets/img/chr5.jpg" alt="" title="annotated atmospheric temperature structure diagram"/>
</div>
<div class="col three caption" style="float: right">
Cartoon representations of the stellar atmosphere, shown in Temperature as a function of atmospheric height, with the density gradient also indicated. The left is a simplified version, showing only the temperature structure of a quiet and active region. On the right, the layers of the atmosphere (photosphere, chromosphere, transition region, and corona) are labeled as well as the region where H&alpha; emission and other atomic lines are formed. In the left margin, I've included a toy diagram of what the surface of active stars to look may like. 
</div>

### variability in H&alpha; emission

H&alpha; emission is intrinsically variable on multiple timescales. The amount of emission we see changes as stars rotate on timescales of hours to days. The magnetic field also changes its configuration as magnetic regions form and dissipate, usually on timescales of months. The overall strength of the magnetic field may have fluctuations over years to decades, analogs of the 11 year Solar cycle. 

Additional spectroscopic monitoring is the key to assigning stars a more fundamental base activity level, and to characterizing the stellar dynamo. I'm currently involved in a project with the Time Domain Spectroscopic Survey of SDSS to measure spectroscopic variability of ultracool dwarfs over year timescales, and have plans to propose further monitoring of activity in the smallest stars and warmest brown dwarfs.


#### Related Publications

{% bibliography -f papers --query @*[group=halpha] %}