# gohsnap_rf
Example code to run trained random forest (RF) regressor. Example applies RF to a subpolar North Atlantic BGC-Argo float.

Training data set: 60 optodes deployed on the OSNAP array (link to data set).

## Statistics & Information
- Training error: 2.51 µmol/kg
- Validation error: 2.81 µmol/kg
- Test error: 2.87 µmol/kg

Features: PSAL, THETA0, DEPTH, LON, YEAR, BATH, DOY_SIN, DOY_COS

The bathymetric data is from GEBCO. 

For additional information on model training and performance, see Miller et al.,.

## References
GEBCO Compilation Group (2024) GEBCO 2024 Grid (doi:10.5285/1c44ce99-0a0d-5f4f-e063-7086abc0ea0f)

Miller UK, Fogaren KE, Atamanchuk D, Johnson C, Koelling J, Le Bras I, Lindeman M, Nagao H, Nicholson DP, Palevsky H, Park E, Yoder M and Palter JB (2024) Oxygen optodes on oceanographic moorings: recommendations for deployment and in situ calibration. Front. Mar. Sci. 11:1441976. https://doi.org/10.3389/fmars.2024.1441976

These data were collected and made freely available by the International Argo Program and the national programs that contribute to it.  (https://argo.ucsd.edu,  https://www.ocean-ops.org).  The Argo Program is part of the Global Ocean Observing System.
