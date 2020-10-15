---
layout: default
description: Research
---

## Retrievals of Low and High Resolution Observations

To find out the properties of the exoplanet atmospheres, such as the H<sub>2</sub>O abundance or the temperature profile, we use retrievals to compare our models against the observations. Retrievals often explore many millions of spectral models to constrain the atmospheric properties in a Bayesian framework. These have been used extensively to analyse observations from the Hubble Space Telescope as well as other low resolution observations. I have developed a new retrieval framework, HyDRA, from the ground up, to efficiently retrieve such low resolution observations. Furthermore, I have also combined the low resolution observations with ground based high resolution data to perform hybrid retrievals. Such retrievals incorporating high resolution data have only very recently been proposed owing to their complexity and computational expense, requiring state of the art computational and statistical tools for efficiency. One of the most promising avenues I have been exploring has been the complementarity of low and high resolution observations, which allows for more stringent constraints on the abundances of species such as H<sub>2</sub>O and CO with the hybrid approach (see below). My paper on these hybrid retrievals has been published in _The Astronomical Journal_ and can be found [here](https://ui.adsabs.harvard.edu/abs/2019AJ....158..228G/abstract).

![image]({{site.baseurl}}/images/histogram.pdf)

## Disequilibrium Retrievals

One of the key questions that characterising exoplanetary atmospheres allows us to tackle is the reasons behind any differences between the observed constraints and theoretical models. By comparing the observed chemical and thermal properties of exoplanet atmospheres to equilibrium models, we can determine any disequilibrium processes that are occurring within the atmosphere. My disequilibrium framework, HyDRA, allows us to do just this. Firstly, I retrieve the atmospheric properties such as the temperature profile and chemical abundances from the observations. These retrieved properties are then used to explore disequilibrium processes which may be present through integration into my self-consistent model, [GENESIS]({{site.baseurl}}/research_projects/self_consistent.html). I have used this model to analyse the atmosphere of WASP-43b, one of the most well studied hot Jupiters with high precision HST and Spitzer observations of the day side. I have found that the atmosphere is consistent with both thermochemical and radiative equilibrium (see figure below). This work has been published in the _Monthly Notices of the Royal Astronomical Society_ and can be found [here](https://ui.adsabs.harvard.edu/abs/2018MNRAS.474..271G/abstract).

![image]({{site.baseurl}}/images/actualretrieved_fm_PT.pdf)
