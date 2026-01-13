---
title: " "
permalink: /publications/
author_profile: true
classes: splash
header:
    overlay_image: https://okhaliukova.github.io/images/CrestedButte.png
---

All of my publications can be found on my <a href="https://scholar.google.com/citations?hl=en&user=d1oePWkAAAAJ" target="_blank">Google Scholar</a>.

# Projects
------
## Nonparametric approach to estimating sums of heavy-tailed distributions
We formulate a nonparametric approach to estimate methane emission distributions, which are often heavy-tailed, by developing a Bayesian extension of the log-histospline (LHSpline) model. The LHSpline method accurately captures tail behavior while simultaneously estimating the bulk of the distribution. It uses a smoothing spline representation of the log-density and performs particularly well for distributions with exponential tails. We improve the original LHSpline method by incorporating Huber loss for smoothing-parameter selection and by developing a full Bayesian estimation framework. Because site-level emissions are commonly computed as the sum of emissions from multiple sources, we further explore direct methods for estimating extreme quantiles of the total emission distribution and avoid the use of Monte Carlo simulations. This approach has broad applicability not only in environmental science but also in finance, insurance, and risk assessment where the distribution of interest often involves the sum of heavy-tailed distributions. We demonstrate the effectiveness of the method through a case study of methane emissions monitoring at an oil and gas production facility in the Appalachian Basin equipped with continuous monitoring sensors. In this setting, high-frequency measurement data enable a detailed characterization of the underlying emission distribution.

<div style="text-align: center;">
  <img src="/images/Lognormal_2.5_1_1000_model_fit_visual_seed3_midpoints_delta085.png" style="max-width: 100%; height: auto;">
</div>


## Cheniere Energy, Inc
**Investigating Aerial Data Preanalysis Schemes and Site-Level Methane Emission Aggregation Methods at Liquefied Natural Gas
Facilities**

Methane observations at liquefied natural gas (LNG) facilities play an important role in characterizing methane
emissions from the natural gas supply chain. The large size and complexity of LNG facilities make quantifying emissions with
ground-based monitoring systems challenging, making aerial platforms one of the preferred methods for detecting and estimating
methane emissions at these sites. However, aerial measurements typically provide a snapshot of emissions at a given instance,
necessitating further analytical steps to infer both annualized emissions and the range of possible emissions at different instances in
time. This study uses aerial measurements at two U.S. LNG facilities from a Quantification, Monitoring, Reporting, and Verification
project to characterize the distribution of temporally averaged emissions (i.e., annualized inventories) and possible site-level
emissions at any given point in time (“instantaneous emissions”). The former provides uncertainty on the aerial measurement
component of measurement-informed annual inventories, while the latter helps contextualize future snapshot measurements, such as
those from aerial surveys or high-resolution satellite platforms, at LNG facilities. We find that instantaneous emissions may fall well
outside of the distribution describing uncertainty in the annual inventory. We also compare different preanalysis schemes for aerial
data, as existing literature does not provide a clear consensus on methods for doing so, especially at LNG facilities. We find the
persistence assumption to be the most critical preanalysis factor.

<div style="text-align: center;">
  <img src="/images/LNG.png" style="max-width: 100%; height: auto;">
</div>


**LNG Aggregation methods paper**: [Methods 2025](https://doi.org/10.1021/acsestair.4c00301)    
**LNG Intensity paper**: [Supply Chain 2025](https://doi.org/10.26434/chemrxiv-2025-8751d)  
**LNG Multiscale Measurements paper**: [Greenhouse Gas Emissions 2024](https://doi.org/10.1021/acs.estlett.4c00713)   
    
• Project: Continuous methane emissions monitoring at an oil and gas production facility.
Evaluated the ability of multiple ground-based continuous monitoring systems to capture emissions dynamics using
time-series analysis and wind-informed modeling.

## Colorado Ongoing Basin Emissions (COBE) Study
• In collaboration with the Colorado State University (CSU) Energy
Institute, utilized high-resolution aircraft measurements to estimate methane emissions at oil and gas production sites
across Colorado (over 11,000 operational facilities) and constructed a joint emissions distribution using aerial data
from three independent monitoring providers.

## Satellite-based methane monitoring
• Processed TROPOMI Level-2 orbit files to generate two
