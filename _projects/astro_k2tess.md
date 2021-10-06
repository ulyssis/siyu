---
layout: page
title: TESS & K2
description: small star variability and flares
img: /assets/img/tess.jpg
importance: 1
category: astronomy
---

The [NASA Kepler](https://www.nasa.gov/mission_pages/kepler/main/index.html) mission, and its successor, [TESS](https://www.nasa.gov/tess-transiting-exoplanet-survey-satellite), aim to find exoplanets that pass in front of their host stars by detecting the decrease in starlight when a small part of the star is blocked by the exoplanet. In the process, they obtain time series data that can reveal stellar flares - sudden outbursts of energy that occur when the surface magnetic field reconnects. 

My collaborators and I look for flares in this time series data, then characterize their energies and overall frequency. We expect the flare frequency to be related to the overall strength of the star's magnetic field - which itself depends on the star's rotation, mass, and age. There are three main projects that I'll introduce here.

#### flares and age using K2 clusters

As stars age, they typically slow their rotation, which weakens the stellar magnetic field. We expect that the frequency of flares should also decrease with age, and if we can measure the relationship between a star's flare rate and its age, flares can be a useful age indicator. First, we must examine flares on stars with well-determined ages. 

A star cluster is a graviationally bound group of stars that were typically formed from the same material at the same time. Within most clusters, all the stars have the same age and chemical composition, so we can determine the cluster age from stars that have more obvious age indicators. [Ekaterina Ilin](https://ekaterinailin.github.io/) is leading a project to examine the flare rate on different types of stars in clusters with K2 data and well-measured ages. 

<div class="img_row">
    <img class="col half left" src="{{ site.baseurl }}/assets/img/FFDtwo.png" alt="" title="normalized emission lines during a large flare"/>
    <img class="col half left" src="{{ site.baseurl }}/assets/img/allflare.png" alt="" title="height of formation of emission lines"/>
</div>
<div class="col three caption" style="float: right">
<b>Left panel:</b> The frequency of flares as a function of energy for two star clusters: M44 (age: 125 Myr) and M45 (age: 625 Myr). For both clusters, small flares occur much more frequently than large flares, but the overall flare rate of the younger cluster is higher. (from: <a href='https://ui.adsabs.harvard.edu/abs/2019A%26A...622A.133I/abstract'>Ilin et al. 2019</a>)
<b>Right panel:</b> A parameterization of overall flare rate as a function of cluster age. The different color points seperate stars of different surface temperatures. Overall the data shows a decrease in flare rate as a function of age andan increase for smaller, cooler stars. (from: <a href='https://speakerdeck.com/ekaterinailin/k2-and-tess'>Ilin talk at Thinkshop 16</a>)
</div>

To reliably identify flares in K2 data, Ekaterina developed the [AltaiPony](https://altaipony.readthedocs.io/en/latest/) flare finding code, an updated version of Jim Davenport's [Appaloosa](https://github.com/jradavenport/appaloosa) code. This fall, she is working to update the first version of the project, which focused on comparing M44 and M45, with four additional clusters and a refined version of the flare injection/recovery testing procedure. 


#### ultracool dwarfs in K2

Despite small masses and cool, mostly neutral atmospheres, many of the coolest stars (and warmest brown dwarfs) still can have dramatic flares. In fact, these stars typically maintain their magnetic field to older ages, so the average ultracool dwarf is typically magnetically active - though often with less overall energy output than more massive stars.  

In work led by Rishi Paudel and John Gizis, we looked for flares in all ultracool dwarfs in Kepler's K2 survey, successfully obtaining short cadence observtions for a dozen dwarfs. We found that flares are actually ubiquitous on ultracool dwarfs--the observed dwarfs flared at lower energies than more massive flare stars, but the flares were still common. 

#### TESS ultracool dwarfs

The TESS mission has been underway for over a year, delivering month-long light-curves for the brightest stars in first the southern hemisphere and, as the second year progresses, the northern hemisphere. My collaborators and I have an accepted proposal for TESS to obtain short cadence observations for a carefully selected sample of the brightest M6 and later dwarfs over the entire sky. 

Analysis of the data is ongoing, but initial data suggests that the overall flare rate for ultracool dwarfs strongly depends on stellar mass, but may be higher than was found by the initial K2 work. 

#### Related Publications

{% bibliography -f papers --query @*[group=k2tess] %}