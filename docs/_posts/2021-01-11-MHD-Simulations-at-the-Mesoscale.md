---
title: MHD Simulations at the Meso-scale
author: Kyle Murphy
layout: post
---

Professor John Lyon from Dartmouth University kicked off the first seminar of the new year discussing the newly developed Grid Agnostic MHD for Extended Applications (GAMERA) global model, mesoscale magnetospheric dynamics and their importance in global modelling. John began with a brief history of global MHD simulations in the 50's and 60's and advances in the 80's which provided higher resolution grids, more advanced algorithms, and more accurate physics. One of these advances was the Total Variation Diminishing (TVD) algorithm which allowed for a better representation of steps in simulation domains. He provided examples of the utility of the TVD algorithm including the linear advection test and the increasing accuracy of the TVD algorithm is with increasing order. John then discussed the divergence of **B** in MHD simulations, the issues that arise when requiring div **B** to be zero, and their potential solutions. Moving on, John provided an overview of the newly developed GAMERA code which implements many key features of it's predecessor while also improving several aspects of the LFM code. He provided examples of GAMERA's utility including simulating the solar wind interaction at Venus and Jupiter; highlighting the importance of higher order simulations for modeling mesoscale dynamics of the solar wind-magnetospheric interaction. John concluded his talk with a discussion of the Center for Geospace Storms, the suite of models coupled to GAMERA, and the utility of GAMERA and the Multiscale Atmosphere-Geospace Environment (MAGE) framework for investigating magnetospheric dyanmics at Earth. In particular he highlighted new work investigating the formation of auroral beads, the role of mesoscale flows in the buildup of the ring current, the dynamics of traveling atmospheric and ionospheric disturbances, and the dynamics of field aligned currents.   

You can find a recording of John's seminar on our [YouTube channel][1] and a copy of his talk [here][2].


[1]:https://www.youtube.com/channel/UCNlOK9mCmI3V111EHQRCuEQ
[2]:https://github.com/MSOLSS/MagSeminars/blob/master/presentations/