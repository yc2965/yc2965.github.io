# Research

My research advances turbulence theory and modeling, investigates climate responses to human-induced land-surface heterogeneities, and identifies key land–atmosphere processes controlling extreme events. I integrate theory, numerical simulations (DNS, LES, and cloud-resolving models), field observations, and machine learning to improve predictions of extreme weather, air quality, and human impacts on climate.

---

## 1) New turbulence theories and modeling techniques for weather and climate models

### 1.1 New velocity/temperature log-law for atmospheric boundary layers  
In global weather and climate models, turbulent exchange of momentum and heat between the surface and atmosphere is commonly represented using Monin–Obukhov similarity theory (MOST). However, MOST performs poorly under strongly stable or strongly unstable conditions. My work shows that buoyancy does not eliminate logarithmic velocity/temperature profiles; instead it modifies the slope of the log law—providing an alternative framework that can improve near-surface predictions in heat waves, droughts, nighttime conditions, winter climate, and polar environments.

- **Logarithmic temperature profile in unstable boundary layers:**  
  [Cheng et al. (2021), *Physical Review Fluids*](https://doi.org/10.1103/PhysRevFluids.6.034606)
- **Logarithmic velocity profiles in stable boundary layers (Editors’ Suggestion):**  
  [Cheng et al. (2023), *Physical Review Fluids*](https://doi.org/10.1103/PhysRevFluids.8.114602)

### 1.2 Deep learning and generative AI for subgrid-scale turbulence modeling  
Large-eddy simulation (LES) resolves only the largest eddies and parameterizes subgrid-scale (SGS) stresses. I develop data-driven SGS closures that learn SGS statistics from DNS across stability regimes. Recent work extends deterministic DNN closures to **generative** modeling with diffusion models (DDPMs), learning conditional distributions of SGS stresses and improving spatial correlations and stress distributions relative to classical closures.

- **DNN-based SGS turbulence closure:**  
  [Cheng et al. (2022), *JAMES*](https://doi.org/10.1029/2021MS002847)
- **Generative AI (DDPM) for SGS stresses:**  
  [Cheng & Liu (2025), arXiv:2510.00383](https://arxiv.org/abs/2510.00383)

### 1.3 New wavenumber regimes for turbulence spectra in stable boundary layers  
Stably stratified turbulence is difficult to represent in NWP and climate models. My work identifies multiple spectral regimes in the stable ABL and highlights missing physical length scales (e.g., buoyancy-related scales) that can guide improved parameterizations.

---

## 2) New turbulence theory for flux observations

### 2.1 Correcting Taylor’s frozen turbulence hypothesis for surface-layer turbulence  
Eddy-covariance measurements often rely on Taylor’s hypothesis to convert single-point temporal measurements into spatial spectra. My work shows Taylor’s hypothesis breaks down for small eddies in the atmospheric surface layer and provides a correction that can improve estimates of turbulent spectra and surface fluxes.

- [Cheng et al. (2017), *Geophysical Research Letters*](https://doi.org/10.1002/2017GL073499)
AGU EOS: [Global Atmospheric Observations May Need Tweaking for Turbulence](https://eos.org/research-spotlights/global-atmospheric-observations-may-need-tweaking-for-turbulence)

### 2.2 Alternate scaling for turbulence cospectra  
High-frequency spectral corrections in eddy-covariance fluxes require an assumed cospectral shape. I showed that a **−2 power-law** scaling is theoretically valid and can better approximate observations than the commonly assumed −7/3 scaling under stable stratification—improving flux corrections, especially for CO₂.

- [Cheng et al. (2020), *Boundary-Layer Meteorology*](https://doi.org/10.1007/s10546-020-00545-6)

---

## 3) New interaction mechanisms between the atmosphere and heterogeneous land surface

### 3.1 Unexpected warming from land radiative management (LRM)  
Land radiative management (e.g., increasing albedo to cool) is often proposed as a climate adaptation/geoengineering strategy. My work shows that LRM can **warm surrounding regions** via unintended impacts on precipitation and soil moisture—highlighting a mechanism by which soil moisture influences precipitation efficiency and re-evaporation.

- [Cheng & McColl (2024), *Geophysical Research Letters*](https://doi.org/10.1029/2024GL112433)
The Guardian: [Why cooling white roofs cause neighbours to swelter](https://www.theguardian.com/news/2024/dec/05/weatherwatch-why-cooling-white-roofs-cause-neighbours-to-swelter)
AGU EOS: [Seemingly Simple Climate Adaptation Strategy Could Backfire](https://eos.org/research-spotlights/seemingly-simple-climate-adaptation-strategy-could-backfire)

### 3.2 Soil Moisture Control of Precipitation Re-evaporation
Soil moisture heterogeneity can induce mesoscale circulations and thus trigger precipitation due to differential heating between dry and wet surfaces. Previous studies suggested that decreasing soil moisture in the dry surface enhances the mesoscale circulation and increases  precipitation over the dry domain. Cheng et al. ([2021, JAS](https://doi.org/10.1175/JAS-D-21-0059.1)) showed that when soil moisture is small in the dry domain, drier soils ultimately lead to less precipitation in the dry domain since precipitation re-evaporation increases, meaning proportionally less water vapor over the dry domain becomes surface precipitation. This work highlights an important new mechanism by which soil moisture controls precipitation, through its impact on precipitation re-evaporation and efficiency.

### 3.3 Roughness-driven thermally direct mesoscale circulations  
Deforestation, urbanization and construction of wind farms can change the land surface roughness, which can further influence surface heat fluxes and thus weather and climate. Land surface roughness anomalies can dynamically trigger convergence through changing mean wind speed. Cheng & McColl ([2023, GRL](https://doi.org/10.1029/2023GL105150)) reported a new mechanism, in which roughness anomalies cause thermally direct mesoscale circulations and anomalous precipitation. We found that anomalously high roughness increases turbulent mixing near the surface, which decreases land surface temperature and outgoing longwave radiation. The additional surface net radiation partly goes into greater sensible heat flux, which triggers mesoscale circulations driven by differential heating. As a result, precipitation over the high-roughness anomaly is generally larger than that over the low-roughness background. This new mechanism, not present in climate models, may be relevant to storm formation over wind farms, cities and forests.

