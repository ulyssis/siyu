---
layout: page
title: cool star kinematics
description: estimating ages from velocities
img:
importance: 9
category: astronomy
---

Each star orbits the center of our Galaxy, and its speed and position depend on its history of interactions with dust and other stars in the Galactic plane. As stars age, they have more and more kinematic interations, which overall increase the total stellar velocity and result in older stars spending more time further from the plane of the Galaxy. Because the changes in orbital motion are a stochastic process, kinematics is only a reliable age indicator when considering populations or groups of stars. 

I mainly use kinematics to examine the usefulness of other age indicators. As part of my dissertaiton, I looked at the J-K colors of L dwarfs compared to kinematics, finding that older stars have bluer J-K colors than younger stars, presumably due to the effects of lower metallicity in older stars or thicker clouds in younger stars. 

<div class="img_row">
    <img class="col one left" src="{{ site.baseurl }}/assets/img/L_JK.png" alt="" title=""/>
    <img class="col two left" src="{{ site.baseurl }}/assets/img/galpos_show.png" alt="" title=""/>
</div>
<div class="col three caption" style="float: right">
<b>Left panel:</b> The velocity dispersion in the three dimensions of motion as a function of color difference from the mean J-K color. The bluer dwarfs (smaller values of J-K) have a larger velocity dispersion (consistent with older ages), while redder dwarfs have a smaller velocity dispersion. From <a href='https://ui.adsabs.harvard.edu/abs/2010AJ....139.1808S/abstract'>Schmidt et al. (2010)</a>
<b>Right panel:</b> The position of dwarfs in the BUD sample relative to the Galactic plane, seperated by spectral type. 
</div>

I am currently working with my BOSS Ultracool Dwarfs sample of 13000 late-M and L dwarfs with spectra from SDSS and Galactic kinematics to examine other properties related to age. Initial results suggest that several colors are related to age, and that magnetic activity and age are related even at these late spectral types where spin-down is less efficient. 


#### Related Publications

{% bibliography -f papers --query @*[group=kine] %}