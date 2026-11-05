# SOCA data

Public data used by SOCA – Sobaie Catchment Analysis (Sobaie Lab).

## HYSOGs250m – hydrologic soil groups (release `hysogs250m`)
A cloud-optimised copy (values unchanged) of:

Ross, C.W., L. Prihodko, J.Y. Anchang, S.S. Kumar, W. Ji, and N.P. Hanan. 2018. *Global Hydrologic Soil Groups (HYSOGs250m) for Curve Number-Based Runoff Modeling.* ORNL DAAC, Oak Ridge, Tennessee, USA. https://doi.org/10.3334/ORNLDAAC/1566

Source: NASA ORNL DAAC. Listed on data.gov as a public U.S. government work. Please cite the dataset above when you use it.

## Large-river map (folder `big-rivers/`)
Rivers with an upstream area of at least 1,000 km² from HydroRIVERS v1.0, split into 10° tiles (`rivers_<lon>_<lat>.npz`, lower-left corner in degrees; `index.json` lists the tiles). SOCA downloads only the tiles around a study area for its large-river check.

Source: Lehner, B., Grill, G. (2013). Global river hydrography and network routing: baseline data and new approaches to study the world's large river systems. *Hydrological Processes* 27(15), 2171–2186. HydroRIVERS © World Wildlife Fund, Inc. (2006–2022), https://www.hydrosheds.org – used under the HydroSHEDS licence (attribution required).
