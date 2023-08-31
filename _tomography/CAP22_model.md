---
title: "CAP22 model available"
excerpt: "North American Absolute arrival-time tomography model: CAP22<br/><img src='/images/2022JB025745-header.png'>"
collection: tomography
date: "2023-02-27"
---

## Summary

<br/><img src='/images/2022JB025745-f06.png'>

CAP22 (Boyce et al., 2023), is an absolute P-wavespeed tomographic model with focus on North American, specifically Canadian and Alaskan mantle structure, provided with and without crustal correction. We incorporate >202,000 absolute arrival time picks from temporary seismograph stations in Canada and Alaska along with USArray and global data sets. Tomographic model, data, arrival time picks, software and plotting codes are all available (see links below).

## Links

* Download the paper [here](/files/Boyce_et_al_2023_JGR_CAP22.pdf).
* Download the supplementary material [here](/files/ESUPP_Boyce_et_al_2023_JGR_CAP22.pdf).
* Download the tomographic model: CAP22 [here](https://doi.org/10.17611/dp/emc.2023.cap22.1).
* Raw data files, processed data (including arrival-time picks), inversion software package and plotting codes are available [here](https://doi.org/10.5281/zenodo.7510591).

## Details

**Citation:**

Boyce, A., Liddell, M. V., Pugh, S., Brown, J., McMurchie, E., Parsons, A., et al. (2023). A new P-wave tomographic model (CAP22) for North America: Implications for the subduction and cratonic metasomatic modification history of western Canada and Alaska. Journal of Geophysical Research: Solid Earth, 128, e2022JB025745. https://doi.org/10.1029/2022JB025745

**Short description:**

CAP22_NACr14_MOD is an adaptively parameterized, global absolute P-wave tomographic model following the methodology of Li et al., (2008). The crustal correction implemented in this model is described in the manuscript and supplementary material. ak135 (Kennett et al., 1995) is used as the global reference model. New data has been added in Canada and Alaska, so we provide only the North American component of the model. While the adaptively parameterized grids at upper mantle depths can be found in the supplementary material of the manuscript, here we provide the model sampled at 0.25x0.25 degrees and 50km depth to facilitate smooth plotting. The 3D grid contains the columns: latitude (deg), longitude (deg), depth (km), dVp (percentage relative to ak135), vp (absolute vp in km/s).

CAP22_MOD is an identical tomographic model to that above but no crustal correction is implemented.

Also available is a resolution/illumination mask for the upper part of the model (CAP22_MASK_5deg). Regions with less than adequate resolution in CAP22 are determined following the methodology of Burdick et al., (2014). Regions where the mask is on (i.e. equal to 1) are regions of low confidence or poor resolution. Regions where the mask is off (i.e. equal to 0) are regions of high confidence or good resolution. Values between these two extremes result from sampling the adaptively parameterized grid at 0.25x0.25 degree intervals to facilitate smooth plotting. Irregular spatial plotting grids result from coordinate rotations applied to the data (see main manuscript) but can be easily resampled for plotting. The 3D grid contains the columns: latitude (deg), longitude (deg), depth (km), mask on (1/0). 

**Dataset description:**

Our global dataset of absolute arrival-time picks includes P, Pn, Pg, pP, PKP, PKiKP and PKIKP phases from the “EHB” database (Engdahl et al., 1998) spanning the period 1964−2004 (Li et al., 2008a) and USArray Transportable Array (TA) data recorded from 2004-2020. We improve resolution in Canada and Alaska by incorporating numerous smaller regional seismic networks. These total 202,719 P arrivals from 8319 earthquakes recorded in North America at 1,562 stations over the period 2002-2020. Further details on analysis of these datasets can be found in the main manuscript.

The file CAP22_phase_SUMMARY.txt contains the details of direct P-phase absolute arrival-time picks derived from networks in Canada and Alaska. The file CAP22_event_SUMMARY.txt contains the details of corresponding earthquakes (See README for more details).

**References:**

Burdick, S. et al. (2014) Model Update January 2013: Upper Mantle Heterogeneity beneath North America from Travel‐Time Tomography with Global and USArray Transportable Array Data. Seismological Research Letters 85, 77–81. https://doi.org/10.1785/0220130098

Engdahl, et al., (1998). Global teleseismic earthquake relocation with improved travel times and procedures for depth determination. Bull. Seismol. Soc. Am. 88, 722–743.

Kennett, et al., (1995). Constraints on seismic velocities in the earth from traveltimes. Geophys. J. Int. 122, 108–124. https://doi.org/10.1111/j.1365-246X.1995.tb03540.x.

Li et al., (2008) A new global model for P wave speed variations in Earth's mantle. Geochem. Geophys. Geosyst., 9, https://doi.org/10.1029/2007GC001806.
