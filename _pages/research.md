---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

My scientific interests include constraining cosmology and baryonic feedback from cosmic shear and galaxy clustering, as well as studies of galaxy cluster properties and cluster cosmology. I am a member of both the Hyper Suprime-Cam (HSC) and Atacama Cosmology Telescope (ACT) collaborations, and am also interested in multi-probe cosmological analyses that utilize cross-correlations of cosmic shear, galaxy clustering, CMB lensing and Compton-y maps. I have also been engaged in a number of projects related to [science and space policy](../science_policy).

## Cosmic Shear
<img src="../images/hscy3_cosmic_shear_constraint.png" alt="HSC Y3 Results" width="500"/>

I recently led the HSC Year 3 analysis of [cosmic shear power spectra](https://arxiv.org/abs/2304.00701). Cosmic shear is a measure of the coherent distortion of light from distant galaxies due to gravitational lensing by the large scale structure of the universe. Cosmic shear is a direct probe of the matter power spectrum, and can therefore be used to constrain the matter fraction in the universe, $\Omega_m$, and the amplitude of density fluctuations on the scale of 8 Mpc/h, $\sigma_8$. My cosmic shear analysis resulted in a 4% precision constraint on the parameter $S_8 \equiv \sigma_8 \sqrt{\Omega_m/0.3} = 0.776^{+0.032}_{-0.033}$, adding to the apparent tension between values of $S_8$ inferred from lensing surveys and those from CMB experiments. 

In addition to the measurement and analysis of the cosmic shear data vector, I have also been involved in projects thinking about the systematics that can contaminate this measurement. In addition to excellent its excellent seeing conditions, HSC is deepest precursor survey to the Vera C. Rubin Observatory, so we are starting to see not only the strength of the data, but also all the systematic effects that we will have to worry about when doing our cosmological analyses. I have contributed to our measurement of the [sample redshift distribution](https://arxiv.org/abs/2211.16516), which uses clustering redshifts from a Luminous Red Galaxy sample, in addition to the photometric information we have for our full galaxy sample, to better constrain the distances to the galaxies we are using to measure cosmic shear. I have also worked on our model for biases in the cosmic shear measurement caused by the [Point Spread Function (PSF)](https://arxiv.org/abs/2212.03257). Although cosmic shear measurements have traditionally only modeled the impact of the second moments of the PSF, we extend the systematics model to higher moments and show that, for HSC Y3, the fourth moment PSF leakage term is the dominant contribution to the bias on the cosmic shear data vector, and that not correcting for this term can lead to significant biases in our cosmological parameter inference.   

## Baryonic Feedback
<img src="../images/Baryonic Feedback.png" alt="Baryonic Feedback" width="500"/>

As seen above, there is a wide range of predictions from different hydrodymanical simulations on how much the power spectrum is suppressed due to baryonic effects such as outflows from Active Galactic Nuclei. In our HSC Y3 cosmic shear analysis, as is the case for weak lensing analyses from other surveys, we had to throw out our measurements at small scales due to uncertainities in the modeling of baryonic feedback. In addition to increasing the range of scales that we can use in our analyses, an accurate feedback model can also help our understanding of the apparent $S_8$ tension, as strong feedback scenarios would allow for a higher value of $S_8$ that is not in tension with the constraints from the CMB. I am currently extending our fiducial HSC Y3 cosmic shear analysis to smaller scales, and exploring different methods of modeling feedback to determine a methodology for achieving unbiased and optimal constraints our cosmological parameters. 

## Tomographic Galaxy Clustering
<img src="../images/HSC Cosmos.jpeg" alt="HSC Galaxies" width="500"/>

I am also leading the HSC Year 3 analysis of tomographic galaxy clustering. We are looking at galaxy clustering angular power spectra in four tomographic redshift bins extending from $z=0.3$ to $z=1.5$. We plan to use these measurements to study different methods for modeling nonlinear galaxy bias, including Halo Occupation Distribution (HOD) models as well as a Hybrid Effective Field Theory approach. We aim to evaluate whether HODs are a sufficient model for HSC data, as well as understand the extent to which we can jointly constrain cosmological parameters and these small scale clustering models. 

## CMB Cross-correlations
<!-- ![HSCxACT](../../images/HSC ACT Footprint.png) -->
<img src="../images/HSC ACT Footprint.png" alt="HSCxACT" width="750"/>

The long-term goal of my thesis is to obtain constraints on both cosmology and small scale (nonlinear) physics by combining the information we get from a galaxy survey like HSC, in the form of cosmic shear and galaxy clustering, with information from the CMB in the form of CMB lensing and thermal Sunyaev-Zeldovich (tSZ) maps from ACT.  In particular, using the tSZ map alongside these other large-scale structure observables will allow us to probe the baryon distribution and thus derive constraints on baryonic feedback effects on the matter power spectrum.

## Galaxy Clusters
<!-- ![CAMIRA Clusters](../../images/CAMIRA Clusters.png) -->
<img src="../images/CAMIRA Clusters.png" alt="CAMIRA Clusters" width="750"/>

In addition to cosmology with the HSC survey, I also study properties of galaxy clusters using the [CAMIRA HSC cluster catalog](https://github.com/oguri/cluster_catalogs). In particular, I have used the extraordinary depth of HSC to study the evolution of Brightest Cluster Galaxies (BCGs) as a function of redshift. BCGs are, by definition, the most luminous galaxies in each cluster, and are likely to have followed a different evolutionary path from other cluster member galaxies, due to processes like galactic cannibalism. This might cause their luminosities to be inconsistent with the overall cluster luminosity distribution, i.e. "special". In [my paper](https://doi.org/10.1093/mnras/stab2363), I showed that BCG luminosities are statistically special from $z=0.3$ all the way to $z=1.0$. This means that any evolutionary process to make them special must have happened earlier than a redshift of $z=1$.

While this work only extended upto a redshift of $z=1$, I am the PI of an ongoing observation program to study clusters at even higher redshifts ($1.0<z<1.2$), in collaboration with Yen-Ting Lin. We use multi-object spectroscopy on the Magellan and Gemini telescopes to get accurate redshifts for photometrically selected clusters from HSC, helping calibrate the redshift determination of the CAMIRA algorithm. By getting spectra for ~30 member galaxies of each cluster, we are able to obtain a velocity dispersion, which we can then use to calibrate the mass-richness relation at such high redshifts. This will be important for reducing uncertainties in future HSC cluster lensing studies. 

I also advise undergraduate students on topics related to cluster physics and cluster cosmology. For more details, please see my [Teaching and Advising](../teaching) page. 
