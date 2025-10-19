## IODP Logging While Drilling: Curated Datasets

*Last updated: October, 2025*

### Data Source

All logging data was sourced from https://mlp.ldeo.columbia.edu/logdb/. Raw datasets were cleaned and combined to form the input datasets for the WellWise machine learning models (see: https://github.com/JennaEverard/WellWise).

### About

Each dataset reports the following measurements:

Parameter | Units & Other Notes |
--- | --- |
depth | reported in meters below sea floor (mbsf). |
gr | natural gamma ray (gr). reported in gAPI. |
d_res | deep (~5 in/12.7 cm) formation electrical resistivity. reported in ohmm. |
s_res | shallow (~1 in/2.5 cm) formation electrical resistivity. reported in ohmm. |
den | density. reported in g/cc. |
vp | p-wave velocity. converted to km/s. |

### Citation

Everard, J., Nicholson, U. (2025, October). From Incomplete Drilling Data to Synthetic Seismograms: Machine Learning Based Prediction of Key LWD Logs for Core-Log-Seismic Integration. In *Geological Society of America Abstracts* (Vol. 57, No. 6, doi: 10.1130/abs/2025AM-7944).
