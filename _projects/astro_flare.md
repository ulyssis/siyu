---
layout: page
title: flaring atmospheres
description: spectroscopic characterization
img: /assets/img/Nasa_EV_Lacertae_250408.jpg
importance: 3
category: astronomy
---

Flares are complicated events that are triggered by the reconnection of magnetic field lines. The dramatic reconnection event accelerates particles into the star's atmosphere, heating many different layers that emit across the electromagnetic spectrum. Time-resolved spectroscopy is a unique tool for understanding the evolution of heating and cooling during stellar flares. Each emission line or continuum enhancement traces a different layer of the atmosphere, so we can estimate the changing temperatures and densities as the flare evolves. 

<div class="img_row">
    <img class="col half left" src="{{ site.baseurl }}/assets/img/reconnection.png" alt="" title="normalized emission lines during a large flare"/>
    <img class="col half left" src="{{ site.baseurl }}/assets/img/uvloops.jpg" alt="" title="height of formation of emission lines"/>
</div>
<div class="col three caption" style="float: right">
<b>Left panel:</b> Diagram of the magnetic reconnection event responsible for Solar and stellar flares. The regions responsible for different types of emission are labeled. (credit: <a href="https://slideplayer.com/slide/13544886/">C. T. Russell</a>; <a href="https://ui.adsabs.harvard.edu/abs/2016RAA....16...28C/abstract">Gennady et al. 2015</a>)
<b>Right panel:</b> Image of the Sun in UV light showing magnetic loops high above the surface. (credit: <a href='https://www.nasa.gov/content/goddard/why-nasa-studies-the-ultraviolet-sun/'>NASA/SDO</a>)
</div>

### infrared emission lines

While flares are common on cool, red dwarfs, they are often difficult to observe because the hot flare emission is primarily observable in bluer wavelengths, while the cool stellar surface is more easily observed in redder and infrared wavelengths. To test if flares could be observed at infrared wavelengths, I monitored some of the most well-known flare stars with both optical photometry and infrared spectroscopy, looking for signs of emission during strong flares. 


<div class="img_row">
    <img class="col two left" src="{{ site.baseurl }}/assets/img/lineratio.png" alt="" title="normalized emission lines during a large flare"/>
    <img class="col one left" src="{{ site.baseurl }}/assets/img/lineheights.png" alt="" title="height of formation of emission lines"/>
</div>
<div class="col three caption" style="float: right">
On the left, the evolution of emisison lines detected throughout the optical and infrared spectrum. The lines that decline quickly cool the plasma efficiently, while those that continue to emit for longer trace regions of the flaring atmosphere that stay hotter longer. On the right, the layers of formation for emission lines in optical and infrared light. From <a href='https://ui.adsabs.harvard.edu/abs/2012ApJ...745...14S'>Schmidt et al. (2012)</a>.
</div>

With nearly 50 hours of monitoring, I found that infrared lines are only found in strong emisison during the most powerful flares. With a sinmple 1D radiative transfer model, I also found that these infrared emission lines traced only the hottest, most diffuse portion of the flaring atmopshere. Infrared lines are not an efficient method for detecting flares, but they do provide a window into a less well-observed portion of the flaring atmopshere. 

### balmer lines and the balmer jump

I've also been involved in projects led by Adam Kowalski centered on spectroscopic flare monitoring in blue and UV spectra focused on examining the balmer lines and the balmer jump compared to thermal continuum. These two components are typically both present in flares, but more impulsive flares tend to have stronger atomic/balmer emission, while more gentle flares have more thermal continuum. As more data is obtained and models become more sophisticated, we can examine the range of heating mechanisms that generate flare emission. 


#### Related Publications
<div class="publications">
{% bibliography -f papers --query @*[group=flareprop]* %}
</div>