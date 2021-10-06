---
layout: page
title: flares with ASAS-SN
description: exploring sparse cadence data
img: /assets/img/asassnL.png
category: astronomy
importance: 7
---

The [All Sky Automated Survey for Supernovae (ASAS-AN)](http://www.astronomy.ohio-state.edu/asassn/index.shtml) scans the sky once a night, looking for supernovae. The survey has also caught some of the largest stellar flares. ASAS-SN is particularly sensitive to dramatic transients, and so easily observes some of the largest flares on the smallest stars. These are particularly strong because of the contrast effect - the stellar atmosphere is particularly faint and cool at the wavelengths where the flare emission is hot and bright. 

Before more modern time domain surveys, the only flares observed on these small stars were shown in H&alpha; and other atomic lines without a strong white-light component. ASAS-SN observed two particularly large white-light flares on ultracool dwarfs with spectral types M8 and L0, ushering in an era where ultracool dwarf flares are known to be relatively common. 

<div class="img_row">
    <img class="col half left" src="{{ site.baseurl }}/assets/img/lc1_fit.png" alt="" title="Lightcurve of flare on L0"/>
    <img class="col half left" src="{{ site.baseurl }}/assets/img/lc2_fit.png" alt="" title="Lightcurve of flare on M8"/>
</div>
<div class="col three caption" style="float: right">
V magnitude as a function of time for the two most dramatic flares found in ASAS-SN, ASASSN-13cb and ASASSN-16ae. At their peak detected brightness, the flares increased total light received from the star by 9 magnitudes (over 3000 times) and 11 magnitudes (over 40000 times) respectively. The ASAS-SN detections are the filled circles, with the quiescent brightness shown as the dashed line. In the inset figure, the flare detections are shown in units of flux, with possible representative flares models shown.
</div>

Interpreting the ASAS-SN data on flares is a challenge. The observations of each stellar flare only include of a few data points taken at some unknown time during the flare event. I designed a method for estimating the energy of these flares based on the sparse cadence data. A handful of detected points can place strong *lower limits* on the total flare energy because it is not physically possible for the heated plasma that generates the emission to cool instantaneously, so the flare must include a decay phase. I used the [Davenport et al.](http://ads.ari.uni-heidelberg.de/abs/2014ApJ...797..122D) empirical flare model to model the rise and decay phases of these flares, making assuming the ASAS-SN observations occurred near the flare peak. 

The energies for the first two flares characterized were consistent with dramatic events - 10<sup>34</sup> erg flares, comparable to the strongest flares on earlier M dwarfs and thousands of times stronger than those detected on the Sun. We then examined the fifty largest flares in the first four years of the survey (2013-2016), finding an expected correlation between H&alpha; activity and confirming the potential of ASAS-SN to find some of the strongest and most fascinating flares. 

Work with ASAS-SN flares continues! I am part of the team working with Romy Rodriguz, an Ohio State Graduate Student, to look at flares on a sample of nearby M dwarfs. As the ASAS-SN survey continues to expand, we expect many more dramatic flares and may be able to calculate the rate of the rarest, largest stellar flares. Additionally, the techniques developed to analyze sparse flares in this bright transient survey can be adapted to understand the flares found in future large sparse cadence surveys, like ZTF and LSST. 

#### Related Publications

{% bibliography -f papers --query @*[group=asassn] %}