---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Research interests
------------------

- Sea ice and ice shelves in the climate system
- Polar meteorology and oceanography
- Ice - ocean interactions in the climate system
- Improvement of the synergetic use of (climate) models and remote sensing products
- Neural networks as parameterisations

Better including ice shelves in global climate models
-----------------------------------------------------
In my current work, I explore ways to better include the effect of melting ice shelves on the Southern Ocean and beyond in global climate simulations. I currently work with the ocean model NEMO and the climate model IPSL-CM.

Melting at the base of Antarctic ice shelves
--------------------------------------------
 In recent years, I worked a lot on investigating parameterisations describing the ocean-induced melt at the base of Antarctic ice shelves for ice sheet models.

**Context**
The melting of the ice shelves where they are in contact with the ocean is one of the largest uncertainty factors in the Antarctic contribution to future sea-level rise. Several parameterisations exist, linking oceanic properties in front of the ice shelf to melt at the base of the ice shelf, to force ice-sheet models.

**Assessment of existing parameterisations**
In our paper, we assess the potential of a range of these existing basal melt parameterisations to emulate basal melt rates simulated by a cavity-resolving ocean model on the circum-Antarctic scale. To do so, we perform two cross-validations, over time and over ice shelves respectively, and re-tune the parameterisations in a perfect model approach, to compare the melt rates produced by the newly tuned parameterisations to the melt rates simulated by the ocean model. We find that the quadratic dependence of melt to thermal forcing without dependency on the individual ice-shelf slope and the plume parameterisation yield the best compromise, in terms of integrated shelf melt and spatial patterns. The box parameterisation, which separates the sub-shelf circulation into boxes, the PICOP parameterisation, which combines the box and plume parameterisation, and quadratic parameterisations with dependency on the ice slope yield basal melt rates further from the model reference. The linear parameterisation cannot be recommended as the resulting integrated ice-shelf melt is comparably furthest from the reference. When using offshore hydrographic input fields in comparison to properties on the continental shelf, all parameterisations perform worse, however the box and the slope-dependent quadratic parameterisations yield the comparably best results. In addition to the new tuning, we provide uncertainty estimates for the tuned parameters.
You can find the paper here: Burgard et al., 2022. A presentation I did to summarise the main messages of this paper can be found here (from 32:00 on).

If you have input temperature and salinity fields or profiles and want to play around with existing melt parameterisations, check out our python package MULTIMELT. 

**Development of new parameterisations using deep learning**
I also worked on the development of a neural-network based parameterisations. With B. Bouissou, a master student (February to June 2022), we started exploring the use of a neural network in the idealised ISOMIP+ setup. The main results are summarised in this conference paper: Bouissou et al., 2022.
I then worked on an application on circum-Antarctic scale and you can find the paper in JAMES here.
The python package MULTIMELT now also includes this neural network parameterisation under the name "DEEPMELT".

**Understanding the response of basal melt to warming in the different parameterisations**
The uncertain sensitivity of Antarctic ice shelf basal melt to ocean warming strongly contributes to uncertainties in sea level projections. Here, we explore the response of five basal melt models to an idealised sub-thermocline warming. The results show a large intermodel spread. For deep regions of presently fast-melting ice shelves, this spread can reach 2 orders of magnitude. Therefore, a consistent calibration to present-day conditions does not guarantee consistent melt sensitivities, and several basal melt forcings should be applied to prevent underestimating uncertainties in sea level projections.
You can find the complete paper in The Cryosphere here: https://tc.copernicus.org/articles/19/2495/2025/

**Using the parameterisations and other advancements to explore the viability of Antarctic ice shelves**
In a collaboration within the "platformist" team at the IGE in Grenoble, we explored the limit of viability of Antarctic ice shelves, i.e. we estimated when it becomes almost impossible for the ice shelves to maintain their present-day shape. We show that for a scenario in which global warming remains largely below 2 °C, only 1 out of 64 ice shelves will become likely non-viable by 2300. For a scenario in which global warming reaches nearly 12 °C by 2300, many ice shelves become non-viable once global warming exceeds 4.5 °C, loss that is mainly due to an increase in ocean-induced melt. By 2150 and 2300, 26 and 38 ice shelves, respectively, become likely non-viable. Loss of ice-sheet regions restrained by these 38 ice shelves represent a sea-level rise potential of 10 m. Our estimates are latest bounds for reaching non-viability, and ice-shelf collapse could occur even earlier, in particular owing to the synergy with hydrofracturing.
You can find the complete paper in Nature here: https://www.nature.com/articles/s41586-025-09657-w

ARC3O - The Arctic Ocean Observation Operator
---------------------------------------------

**The history behind ARC3O**
The diversity in sea ice concentration observational estimates affects our understanding of past and future sea ice evolution as it inhibits reliable climate model evaluation [Notz et al., 2013] and initialization [Bunzel et al., 2016]. It also limits our ability to fully exploit relationships between the evolution of sea ice and other climate variables, such as global-mean surface temperature [Niederdrenk & Notz, 2018] and CO2 emissions [Notz & Stroeve, 2016].

To address these issues, during my PhD, we have constructed an observation operator for the Arctic Ocean at the frequency of 6.9 GHz. This operator provides an alternative approach for climate model evaluation and initialization with satellite observations.

The ARCtic Ocean Observation Operator (ARC3O) provides the possibility to simulate top-of-the-atmosphere brightness temperatures for the Arctic Ocean area at 6.9 GHz, vertical polarization, from climate model output. This simulated brightness temperature can be compared to brightness temperatures measured by satellites from space.
You can check out the two publications explaining the method and evaluation of ARC3O: Burgard et al., 2020 (a) and Burgard et al., 2020 (b).

**Can I use ARC3O?**
Yes, please! You can download the source code on github or install it directly in python via pip or conda.
The full documentation can be found here.
Arctic Ocean warming in CMIP5 models
As part of my master's thesis and early PhD work, we investigated changes in the Arctic Ocean energy budget simulated by 26 general circulation models from the CMIP5 framework to understandwhether the Arctic Ocean warming between 1961 and 2099 is primarily driven by changes in the net atmospheric surface flux or by changes in themeridional oceanic heat flux. We found that the models strongly disagree, due to different changes in the meridional oceanic heat flux.
Read more: Burgard and Notz (2017).

Supervision
-----------

- Helen Ockenden's postdoc within the project AIAI. Since August 2024.
- Jacquemine Delfieu's master internship. Title: "Exploring the representation of Prydz Bay dense water in NEMO CMIP6 models". February to July 2025. Co-supervised with Katherine Hutchinson.
- Georgia McQuade's master internship. Title: "Etude de l’influence de la résolution spatiale sur la simulation des cavités sous les plateformes de glace en Antarctique". May to July 2024.
- Benjamin Bouissou's master internship. Title: "Parameterization of basal melting of an ice shelf with idealized geometry via a neural network". February to June 2022.

Conferences and workshops
-------------------------

2024

    Joint Committee on Ice Ocean Interactions Workshop, online, October 2024 - Keynote presentation
    Southern Ocean Summer School, Corsica, France, May 2024
    EGU 2024, Vienna, Austria, April 2024 - Highlight presentation
    OCCD Colloquium, GEOMAR, Kiel, Germany, January 2024 - Invited Presentation


2023

    Forum for Research into Ice Shelf Processes 2023, Stalheim, Norway, June 2023 - Poster
    EGU 2023, Vienna, Austria, April 2023 - Poster
    GISS Sea Level Rise Seminar, NASA GISS, online, February 2023 - Invited presentation
    Cryosphere BXL seminar, VUB and ULB, Brussels, Belgium, February 2023 - Invited presentation
    IGS Global Seminar Series, online, February 2023 - Presentation (link)
    Polar Oceans Seminar, British Antarctic Survey, Cambridge, UK, January 2023 - Presentation


2022

    H2020 PROTECT Fall Meeting, Grenoble, France, October 2022 - Keynote presentation
    Forum for Research into Ice Shelf Processes 2022, Northumbria, UK, September 2022 - Presentation
    ECCOMAS 2022, Oslo, Norway, June 2022 - Session convener and Presentation
    EGU 2022, Vienna, Austria, May 2022 - Presentation
    Ocean Sciences Meeting 2022, online, March 2022 - virtual presentation


2021

    H2020 PROTECT Fall Meeting, online, September 2021 - virtual poster
    H2020 PROTECT Spring Meeting, online, May 2021 - virtual poster
    vEGU 2021, online, April 2021 - vPICO presentation


2020

    shareEGU 2020, online, May 2020 - PICO presentation (highlight) and convener of a webinar short course (link)


2019

    GeoScience Communication School, Trieste, Italy, September 2019
    IGS Symposium "Sea Ice at the Interface", Winnipeg, Canada, August 2019 - Presentation
    Snow Winter School, Hailuoto, Finland, February 2019
    European Security Seminar - North, George C. Marshall Center, Garmisch-Partenkirchen, February 2019 - Invited Presentation


2018

    3 Cluster Conference, Berlin, Germany, September 2018 - Invited Presentation
    POLAR2018, Davos, Switzerland, June 2018 - Presentation
    Polar Prediction School, Abisko, Sweden, April 2018
    Arctic System Change Workshop, NCAR, Boulder, USA, April 2018- Poster
    Cryospheric and Polar Processes Seminar, NSIDC, Boulder, USA, February 2018 - Presentation


2017

    Workshop on improved satellite retrievals of sea-ice concentration and sea-ice thickness for climate applications, Hamburg, Germany, October 2017 - Invited Presentation
    Max Planck Visions in Science Conference, Berlin, Germany, September 2017 - Organisation Team
    Workshop on Multi-scale modelling of ice characteristics and behavior, Cambridge, UK, September 2017 - Poster
    Summer School on Earth System Modelling, Hamburg, Germany, September 2017
    EGU 2017, Vienna, Austria, April 2017 - Poster and co-convener of two short courses
    Polar Prediction Workshop & 2nd Sea Ice MIP Meeting, Bremerhaven, Germany, March 2017 - Presentation


2016

    NERC Advanced Training Course - Earth Observations for Weather and Climate Studies, Reading, UK, September 2016 - Poster
    EGU 2016, Vienna, Austria, April 2016 - Poster


2014

    Arctic Climate Change, Economy and Society and Arctic Resilience Report Summer School, Stockholm, Sweden, September 2014