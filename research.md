# Research

My research has focused on advancing turbulence theory and modeling, investigating climate responses to man-made land surface heterogeneities, and identifying the key land–atmosphere processes controlling extreme events. By integrating theory, numerical simulations (DNS, LES, cloud-resolving models), field experiments, and machine learning, my goal is to provide more accurate predictions of extreme weather, air quality, and the impact of human activity on climate, and to strengthen resilience to extremes and promote sustainable land–climate management. 

---

## 1) New turbulence theories and modeling techniques for weather and climate models

### 1.1 New velocity/temperature log-law for atmospheric boundary layers  
Editors' Suggestion at Physical Review Fluids
In global weather and climate models, the exchange of momentum, heat, moisture and carbon dioxide between the Earth’s surface and the atmosphere is constrained by turbulent motion of the air and has been described by a flux-gradient relationship named Monin-Obukhov similarity theory (MOST) since 1954. However, it has long been recognized that MOST cannot correctly capture the turbulent flux transport when the air is significantly cooled or heated by the land surface. A fundamental assumption of MOST is that velocity and temperature near the Earth’s surface do not follow a logarithmic profile due to buoyancy effects. In contrast to MOST, [Cheng et al. 2021, PRF](https://doi.org/10.1103/PhysRevFluids.6.034606) and [Cheng et al. 2023](https://doi.org/10.1103/PhysRevFluids.8.114602), PRF found that buoyancy does not change the logarithmic nature of velocity and temperature profiles but instead modifies the slope of the log law. The proposed log law overcomes the failure of MOST in extreme stability conditions. The proposed logarithmic profile can serve as an alternative to MOST, possibly leading to more realistic predictions of near-surface air temperature, especially in heat waves and droughts, as well as nighttime and winter climate and air quality, especially in polar regions.



### 1.2 Deep learning and generative AI for subgrid-scale turbulence modeling  
The large-eddy simulation (LES) technique only resolves filtered eddy motions and parameterizes the impact of subgrid-scale (SGS) turbulence as a function of the resolved flow. Cheng et al. ([2022, JAMES](https://doi.org/10.1029/2021MS002847)) applied supervised deep neural networks (DNNs) to learn SGS stresses from a set of neighboring coarse-grained velocity from direct numerical simulations across stability conditions from near neutral to very unstable in the atmospheric boundary layer. The DNN model can capture both SGS stresses and dissipation, which is challenging for traditional SGS models like the Smagorinsky model.

Cheng et al. [2025 arxiv](https://arxiv.org/abs/2510.00383) developed a generative AI framework, denoising diffusion probabilistic models (DDPMs), to reconstruct subgrid-scale stresses in large-eddy simulations. By learning conditional distributions rather than pointwise values, this approach outperforms classical closures and prior deep learning models, opening a new direction for SGS modeling in three-dimensional turbulence at high Reynolds numbers.


### 1.3 New wavenumber regimes for turbulence spectra in stable boundary layers  
Stably stratified turbulence in the ABL is very difficult to be represented in numerical weather prediction (NWP) and climate models. Cheng et al. ([2020, JGR Atmospheres](https://doi.org/10.1029/2019JD032191)) showed for the first time that three regimes exist in turbulent kinetic energy (TKE) spectra of the stable ABL and pointed out an important length scale, the buoyancy scale, that is missing in current turbulence parameterization. This study can further guide the development of turbulence parameterization for the stably stratified ABL, especially over the Arctic where climate change is amplified.

---

## 2) New turbulence theory for flux observations

### 2.1 Correcting Taylor’s frozen turbulence hypothesis for surface-layer turbulence  
AGU EOS: [Global Atmospheric Observations May Need Tweaking for Turbulence](https://eos.org/research-spotlights/global-atmospheric-observations-may-need-tweaking-for-turbulence)
Global eddy-covariance measurements of atmospheric surface fluxes of momentum, heat, water vapor and CO2 fluxes rely on Taylor’s frozen turbulence hypothesis, which transforms single-point temporal observations into spatial spectrum. Cheng et al. ([2017, GRL](https://doi.org/10.1002/2017GL073499)) found the relationship between eddy size and advection velocity and showed that small eddies lose their coherent properties due to turbulent diffusion and advect at smaller velocities than large eddies, i.e., Taylor’s hypothesis does not work for small eddies. The study also proposed a correction for single-point measurements of temporal velocity and scalars to improve estimates of surface turbulent energy and CO2 fluxes.


### 2.2 Alternate scaling for turbulence cospectra  
An assumed cospectral shape is required for high-frequency spectral corrections of turbulent fluxes of momentum, heat, water vapor and CO2 fluxes in global eddy-covariance measurements. Cheng et al. ([2020, BLM](https://doi.org/10.1007/s10546-020-00545-6)) showed that a -2 power-law scaling for turbulence cospectra is valid within dimensional analysis and is a better approximation than a typically assumed -7/3 scaling across various field measurements in stably stratified ABL at high Reynolds number. The proposed -2 scaling should improve global eddy-covariance measurement of surface fluxes especially for CO2 flux that is quite sensitive to the cospectra shape.


---

## 3) New interaction mechanisms between the atmosphere and heterogeneous land surface

### 3.1 Unexpected warming from land radiative management (LRM)  

The Guardian: [Why cooling white roofs cause neighbours to swelter](https://www.theguardian.com/news/2024/dec/05/weatherwatch-why-cooling-white-roofs-cause-neighbours-to-swelter)
AGU EOS: [Seemingly Simple Climate Adaptation Strategy Could Backfire](https://eos.org/research-spotlights/seemingly-simple-climate-adaptation-strategy-could-backfire)
Land radiative management (LRM) -- deliberately increasing surface albedo to decrease temperatures -- has been proposed as a form of geoengineering to mitigate the effects of regional warming. Cheng and McColl ([2024, GRL](https://doi.org/10.1029/2024GL112433)) showed that, contrary to expectations, LRM causes temperatures to increase in surrounding regions. The basic reason for the increase is unintended impacts on precipitation. Anomalously low precipitation forms over the LRM region, further decreasing precipitation in nearby areas unprotected by LRM, due to advection and turbulent diffusion. The reduction in precipitation and soil moisture in these regions leads to higher temperatures than would be expected in the absence of LRM. The resulting warming outside the LRM region is comparable to the cooling achieved inside it. This implies that, if wealthy regions unilaterally adopt LRM to cool, their neighbours may experience warming, worsening heat inequality.



### 3.2 Soil Moisture Control of Precipitation Re-evaporation
Soil moisture heterogeneity can induce mesoscale circulations and thus trigger precipitation due to differential heating between dry and wet surfaces. Previous studies suggested that decreasing soil moisture in the dry surface enhances the mesoscale circulation and increases  precipitation over the dry domain. Cheng et al. ([2021, JAS](https://doi.org/10.1175/JAS-D-21-0059.1)) showed that when soil moisture is small in the dry domain, drier soils ultimately lead to less precipitation in the dry domain since precipitation re-evaporation increases, meaning proportionally less water vapor over the dry domain becomes surface precipitation. This work highlights an important new mechanism by which soil moisture controls precipitation, through its impact on precipitation re-evaporation and efficiency.

### 3.3 Roughness-driven thermally direct mesoscale circulations  
Deforestation, urbanization and construction of wind farms can change the land surface roughness, which can further influence surface heat fluxes and thus weather and climate. Land surface roughness anomalies can dynamically trigger convergence through changing mean wind speed. Cheng & McColl ([2023, GRL](https://doi.org/10.1029/2023GL105150)) reported a new mechanism, in which roughness anomalies cause thermally direct mesoscale circulations and anomalous precipitation. We found that anomalously high roughness increases turbulent mixing near the surface, which decreases land surface temperature and outgoing longwave radiation. The additional surface net radiation partly goes into greater sensible heat flux, which triggers mesoscale circulations driven by differential heating. As a result, precipitation over the high-roughness anomaly is generally larger than that over the low-roughness background. This new mechanism, not present in climate models, may be relevant to storm formation over wind farms, cities and forests.

