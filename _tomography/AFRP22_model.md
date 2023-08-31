---
title: "AFRP22 model available"
excerpt: "African Absolute arrival-time tomography model: AFRP22<br/><img src='/images/2022GC010775-header.png'>"
collection: tomography
date: "2023-08-03"
---

## Summary

<br/><img src='/images/2022GC010775-f04.jpg'>

AFRP22 (Boyce et al., 2023), is an adaptively parameterized, absolute P-wave tomographic model for Africa provided with and without crustal correction. Here we focus attention on the East African rift using new data from the TRAILS project in the Turkana depression. Tomographic model, data, arrival time picks, software and plotting codes are all available (see links below).

## Links

* Download the paper [here](/files/Boyce_et_al_2023_GCUBED_AFRP22_RFs.pdf).
* Download the supplementary material [here](/files/ESUPP_Boyce_et_al_2023_GCUBED_AFRP22_RFs.pdf).
* Download the tomographic model: AFRP22 [here](https://doi.org/10.17611/dp/emc.2023.afrp22.1).
* Raw data files, processed data (including arrival-time picks), inversion software package and plotting codes will be available after embargo [here](https://doi.org/10.5281/zenodo.7607098).

## Details


**Citation:**

Boyce, A., Kounoudis, R., Bastow, I. D., Cottaar, S., Ebinger, C. J., & Ogden, C. S. (2023). Mantle wavespeed and discontinuity structure below East Africa: Implications for Cenozoic hotspot tectonism and the development of the Turkana Depression. Geochemistry, Geophysics, Geosystems, 24, e2022GC010775. https://doi.org/10.1029/2022GC010775


**Short description:**

AFRP22_RF_CR1_MOD is an adaptively parameterized, global absolute P-wave tomographic model following the methodology of Li et al., (2008). The crustal correction implemented in this model is described in the manuscript and supplementary material. ak135 (Kennett et al., 1995) is used as the global reference model. New data has been added in the Turkana Depression, Uganda, Mozambique and Namibia, so we provide only the African component of the model. While the adaptively parameterized grids at upper mantle depths can be found in the supplementary material of the manuscript, here we provide the model sampled at 0.25×0.25 degrees and 50km depth to facilitate smooth plotting. The 3D grid contains the columns: latitude (deg), longitude (deg), depth (km), dVp (percentage relative to ak135), vp (absolute vp in km/s).

AFRP22_MOD is an identical tomographic model to that above but no crustal correction is implemented.

Also available is a resolution/illumination mask for the upper part of the model (AFRP22_MASK). Regions with less favourable illumination are determined following the methodology of Boyce et al., (2021). The global data set will of course further illuminate the mantle wavespeed structure so this acts to show the areas better resolved using the new data. Regions where the mask is on (i.e. equal to 1) are regions of low confidence or poor resolution. Regions where the mask is off (i.e. equal to 0) are regions of high confidence or good resolution. Any values between these two extremes result from sampling the adaptively parameterized grid at 0.25×0.25 degree intervals to facilitate smooth plotting. The 3D grid contains the columns: latitude (deg), longitude (deg), depth (km), mask on (1/0).
 

**Dataset description:**

Our global data set of absolute arrival-time picks includes P, Pn, Pg, pP, PKP, PKiKP and PKIKP phases from the “EHB” database (Engdahl et al., 1998), spanning the period 1964-2004 (Li et al., 2008). To constrain the African mantle, we use our previously published data set (Boyce et al., 2021). Here we improve resolution, especially in the Turkana Depression and Uganada, using newly available seismograph networks by adding >14,500 absolute arrival-times from P, PKP, PKiKP and PKIKP phases. Further details on analysis of these datasets can be found in the main manuscript. The raw data files, processed data, inversion software package and plotting codes will be available at https://doi.org/10.5281/zenodo.7607098 following removal of data embargo on 2024-05-24.


**References:**

Engdahl, et al., (1998). Global teleseismic earthquake relocation with improved travel times and procedures for depth determination. Bull. Seismol. Soc. Am. 88, 722–743.

Kennett, et al., (1995). Constraints on seismic velocities in the earth from traveltimes. Geophys. J. Int. 122, 108–124. https://doi.org/https://doi.org/10.1111/j.1365-246X.1995.tb03540.x.

Li et al., (2008) A new global model for P wave speed variations in Earth’s mantle. Geochem. Geophys. Geosyst., 9, https://doi.org/https://doi.org/10.1029/2007GC001806.

Boyce, A. Bastow, I.D. Cottaar, S. Kounoudis, R. Guilloud De Courbeville, J. Caunt, E. Desai, S. (2021), AFRP20: New P-wavespeed Model for the African Mantle Reveals Two Whole-Mantle Plumes Below East Africa and Neoproterozoic Modification of the Tanzania Craton, Geochem. Geophys. Geosyst., https://doi.org/https://doi.org/10.1029/2020GC009302.