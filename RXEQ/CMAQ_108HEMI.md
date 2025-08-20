Northern Hemisphere CMAQ Simulations
=====================================

Annual simulations for 2000 through 2023 were done for the Northern Hemisphere using a modified version of CMAQv5.4 (epa.gov/cmaq) using the CB6R5M_AE7_AQ mechanism updated to include aerosol nitrate photolysis as described in Sarwar et al. (2024). 

The following is a list of input files and science options used in these hemispheric CMAQ simulations.

- Chemical mechanism: cb6r5m updated to include aerosol nitrate photolysis as described in Sarwar et al. (2024)
- Aerosol module: aero7
- Domain: Northern Hemisphere using a 108 km grid size and Polar Stereographic projection assuming a spherical earth with radius 6370.0 km.
- Vertical Resolution: 44 layers from the surface to 50 mb
- Meteorological fields: WRF4.4.1
- Emissions: 2019 HTAP v3.0 anthropogenic emissions + GEIA lightning NO + CAMS biogenic VOC + CAMS soil NO.
- No bi-directional NH3 air-surface exchange
- STAGE (E20) module for dry deposition
- Windblown dust module turned on

**Preliminary Evaluations**:

* [Quarterly O3 and CO vertical profile comparison against IAGOS measurements](./CMAQ_HEMI_iagos.md)
* [Southwest U.S. region O3 for Spring and Summer 2023](./CMAQ_108HEMI_SWUSeval.md)

**References**: 

Sarwar, G., Henderson, B.H., Hogrefe, C., Mathur, R., Gilliam, R., Callaghan, A., B., Lee, J., Carpenter, L. J., 2024: Examining the Impact of the photolysis of aerosol nitrate over Northern Hemisphere, Science of the Total Environment, 917, 170406, 2024.
