Last update: 2023-02-08

---
**Bibliography**

List of references about sea ice - Atmospheric Boundary Layer coupling. I sorted out the references in the 5 categories below:
[TOC]

---

# 1. Atmospheric models (often LES) with prescribed sea ice boundary conditions. 

The focus of these studies is on the response of the ABL to various sea ice boundary conditions (nothing i could find about the feedback effects on sea ice).

* **Michaelis, Lupkes et al 2022 Modelling and parametrization of the convective flow over leads in sea ice and comparison with airborne observations** https://rmets.onlinelibrary.wiley.com/doi/full/10.1002/qj.3953.    METRAS atmospheric model.

* **Wenta, M., & Herman, A. (2018). The influence of the spatial distribution of leads and ice floes on the atmospheric boundary layer over fragmented sea ice.**  https://www.cambridge.org/core/services/aop-cambridge-core/content/view/4961E8E20BC30618A7849378985EA7FA/S0260305518000150a.pdf/
*Investigate the response of the atmospheric boundary layer (ABL) to subgrid-scale variations of sea ice*
*properties and fracturing*
*analyze three-dimensional air circulation within the ABL over fragmented sea ice. A series of idealized high-resolution simulations with Polar WRF is performed for several spatial distributions of ice floes and leads for two values of sea ice concentration (0.5 and 0.9) and several ambient wind speed profiles. Suggests the need for developing suitable parametrizations of ABL effects related to subgrid scale sea ice features for these models.*
[image:11AD9B6B-7A99-4FA1-AADC-95464B492E16-601-00001F4D196CF5DC/Screenshot 2023-02-08 at 12.14.20.png]

* **2019 Spall M. : Dynamics and Thermodynamics of the Mean Transpolar Drift and Ice Thickness in the Arctic Ocean**.  https://doi.org/10.1175/JCLI-D-19-0252.1
*A theory for the mean ice thickness and the Transpolar Drift in the Arctic Ocean is developed.* *Two distinct regimes: a thin ice regime in the eastern Arctic and a thick ice regime in the western Arctic. In the eastern Arctic, the ice drift is controlled by a balance between wind and ocean drag, while the ice thickness is controlled by heat loss to the atmosphere. In contrast, in the western Arctic, the ice thickness is determined by a balance between wind and internal ice stress, while the drift is indirectly controlled by heat loss to the atmosphere.*  T*he basic predictions for ice thickness, heat loss, ice volume, and ice export from the theory compare well with an idealized, coupled ocean–ice numerical model over a wide range of parameter space.* 
*Analytical work compared to an idealised MITgcm simulation (EVP rheology) forced with bulks.*

* **Renfrew 2019 Atmospheric sensitivity to marginal-ice-zone drag: Local and global responses** https://rmets.onlinelibrary.wiley.com/doi/full/10.1002/qj.3486 
*MetUM atmospheric mode and prescribed surface conditions. Surface drag and Form drag.* 

* **Tetzlaff A (2016) Convective processes in the polar atmospheric boundary layer: a study based on measurements and modelling.** (PhD. thesis, Alfred-Wegener-Institut Helmholtz-Zentrum fümlr Polar- und Meeresforschung), p. 136. 
*The https://media.suub.uni-bremen.de/handle/elib/992 of this thesis lies on improving our current understanding of convective processes and the related turbulent fluxes in the polar atmospheric boundary layer (ABL) over both the sea ice covered regions and over the open ocean at the sea ice edge. Obs (aircraft)-based results are supplemented by modeling studies using a simple boxmodel and a one-dimensional mesoscale model. For this purpose, we use a 1D version of the MEsoscale TRAnsport and Stream model (METRAS, Schlünzen, 1988), which is non-hydrostatic and anelastic. The applied parametrisations are a mixing length
closure (ML), a counter-gradient closure (CG), and a so-called eddy-diffusivity mass-flux closure
(EDMF),*

* **Pithan et al 2016. Select strengths and biases of models in representing the Arctic winter boundary layer over sea ice: the Larcform 1 single column model intercomparison**
  https://doi.org/10.1002/2016MS000630
ABL 1D single column in Lagrangian form. Prescribed sea ice conditions.

* **Sea & Yang 2013 Dynamical response of the Arctic atmospheric boundary layer process to uncertainties in sea-ice concentration**
https://doi.org/10.1002/2013JD020312
Polar WRF and prescribed sea ice conditions

* **Bromwich 2009 Development and testing of Polar Weather Research and Forecasting model: 2. Arctic Ocean** https://doi.org/10.1029/2008JD010300
Polar WRF: 25-km resolution

* **Moeng et al 2007   Examining Two-Way Grid Nesting for Large Eddy Simulation of the PBL Using the WRF Model**
https://journals.ametsoc.org/view/journals/mwre/135/6/mwr3406.1.xml
*Two-way nesting for large eddy simulation (LES) of PBL turbulence I*
*A pair of LES-within-LES experiments are performed where a finer-grid LES covering a smaller horizontal domain is nested inside a coarser-grid LES covering a larger horizontal domain. Free-convection and pure shear-driven PBLs. The free-convection case has zero mean wind and the only driving force for turbulence is uniform surface heating.*

* **Zulauf 2002 Two-dimensional cloud-resolving modeling of the atmospheric effects of Arctic leads based upon midwinter conditions at the Surface Heat Budget of the Arctic Ocean ice camp**https://doi.org/10.1029/2002JD002643 Cloud-resolving model + SHEBA-derived fluxes. 

* **Birnbaum & Lüpkes 2002 A new parameterization of surface drag in the marginal sea ice zone** https://a.tellusjournals.se/article/10.3402/tellusa.v54i1.12121/
METRAS ABL model and prescribed surface conditions


---
# 2. Coupled systems (seaice-ocean-atmoshpere)
* **Ren et al 2021:** **A fully coupled Arctic sea-ice–ocean–atmosphere model (ArcIOAM v1.0) based on C-Coupler2: model description**
**and preliminary results** : https://doi.org/10.5194/gmd-14-1101-2021
Polar WRF coupled to MITGCM (VP rheology) at 18km.
*Goal: provide reliable Arctic sea ice prediction on SEASONAL timescales.  Compare a MITGCM forced config with a coupled config with Polar WRF. “The two-way coupling has better performance in terms of sea ice extent, concen- tration, thickness and sea surface temperature (SST), especially in summer. This result indicates that sea-ice–ocean– atmosphere interaction plays a crucial role in controlling Arctic summertime sea ice distribution. “*

* **2022:  Day et all Benefits and challenges of dynamic sea ice for weather forecasts** https://wcd.copernicus.org/articles/3/713/2022/
	- *ECMWF IFS atmospheric forecast experiments. one in which dynamic cou-*
*pling with sea ice concentration and ocean is switched on*
*(coup-SSTSIC), one atmosphere-only where sea ice concen-*
*tration and SST anomalies are persisted from the initial time*
*(pers-SSTSIC), and another atmosphere-only with updated*
*observed sea ice concentration and SSTs (obs-SSTSIC).*
	- *For the coupled forecasts (coup-SSTSIC), the IFS atmo-*
*sphere is coupled to NEMO (Madec, 2008) model version*
*3.4.1 and LIM2, using the ORCA025 horizontal grid (with*
*a resolution of approximately ∼ 10 km in the Arctic) with*
*75 levels in the vertical.*
	- *“Demonstrate that using a dynamically coupled ocean and sea ice model in the European Centre for Medium- Range Weather Forecasts (ECMWF) Integrated Forecasting System results in improved sea ice edge position forecasts in the Northern Hemisphere in the medium range. Further, this improves forecasts of boundary layer temperature and humidity downstream of the sea ice edge in some regions during periods of rapid change in the sea ice, compared to forecasts in which the sea surface temperature anomalies and sea ice concentration do not evolve throughout the forecasts. “*

* **Smith et al 2018 Impact of Coupling with an Ice–Ocean Model on Global Medium-Range NWP Forecast Skill**
https://journals.ametsoc.org/view/journals/mwre/146/4/mwr-d-17-0157.1.xml
NEMO-CICE coupled to GEM for atm.
EVP 25km resolution.
* 
* **Yang et al 2016: Taking into Account Atmospheric Uncertainty Improves Sequential Assimilation of SMOS Sea Ice Thickness Data in an Ice–Ocean Model**  https://journals.ametsoc.org/view/journals/atot/33/3/jtech-d-15-0176_1.xml
*The goal is Data assimilation (of sea ice obs). MITgcm with VP rheology. Forced by ensemble atmospheric forecast.*

* **Horvat 2016 Interaction of sea ice floe size, ocean eddies, and sea ice melting** https://doi.org/10.1002/2016GL069742
MITgcm ocean-ice

* **2004 Pellerin et al Impact of a Two-Way Coupling between an Atmospheric and an Ocean-Ice Model over the Gulf of St. Lawrence**
https://doi.org/10.1175/1520-0493(2004)132<1379:IOATCB>2.0.CO;2 
*Abstract: The purpose of this study is to present the impacts of a fully interactive coupling between an atmospheric and a sea ice model over the Gulf of St. Lawrence, Canada. The impacts are assessed in terms of the atmospheric and sea ice forecasts produced by the coupled numerical system. The ocean-ice model has been developed at the Maurice Lamontagne Institute, where it runs operationally at a horizontal resolution of 5 km and is driven (one-way coupling) by atmospheric model forecasts provided by the Meteorological Service of Canada (MSC). In this paper the importance of two-way coupling is assessed by comparing the one-way coupled version with a two-way coupled version in which the atmospheric model interacts with the sea ice model during the simulation. The impacts are examined for a case in which the sea ice conditions are changing rapidly. Two atmospheric model configurations have been studied. The first one has a horizontal grid spacing of 24 km, which is the operational configuration used at the Canadian Meteorological Centre. The second one is a high-resolution configuration with a **4-km horizontal grid spacing**. A 48-h forecast has been validated using satellite images for the ice and the clouds, and also using the air temperature and precipitation observations. It is shown that the two-way coupled system improves the atmospheric forecast and has a **direct impact on the sea ice forecast.** It is also found that forecasts are improved with a fine resolution that better resolves the physical events, fluxes, and forcing. The coupling technique is also briefly described and discussed.*


---
# 3. Observations of the Arctic ABL
* **Overland et al 1999 Regional sensible and radiative heat flux estimates for the winter Arctic during the Surface Heat Budget of the Arctic Ocean (SHEBA) experiment**
https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/1999JC000010
SHEBA campaign

* **2012 Lupkes et al:  A parametrization, based on sea ice morphology, of the neutral atmospheric drag coefficients for weather prediction and climate models**
*A hierarchy of parametrizations of the neutral 10 m drag coefficients over polar sea ice with different morphology regimes is derived on the basis of a partitioning concept that splits the total surface drag into contributions of skin drag and form drag.*

* **2009 Andreas et al. Parameterizing Turbulent Exchange over Sea Ice in Winter**. *Based on SHEBA campaign data. This paper develops a bulk turbulent flux algorithm to explain the winter data.*



---
# 4. Sea ice models forced with atmospheric boundary conditions
* Heorton et 2014 **The Response of the Sea Ice Edge to Atmospheric and Oceanic Jet Formation** https://doi.org/10.1175/JPO-D-13-0184.1
CICE model forced by idealised atmospheric forcing.


---
# 5. Sea ice model coupled to simple  ABL
Nothing! ?
