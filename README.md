# DUEDARE_multiple_participants
Code to accompany paper on PM inferences with biometrics on multiple participants

Code to accompany (unpublished) paper: Gauging Size Resolved Ambient Particulate Matter Concentration Solely Using Biometric Observations:  A Machine Learning and Causal Approach

### Overview
---
This repo contains both the data and the code to reproduce the analysis and figures shown in the paper simply using a jupyter notebook. 

- assets/
  - static_bike_ride_pm.pkl - pickle file containing all pre-processed biometric and particulate matter (PM) data 
  - traversal_order_biometrics.csv - csv file containing a handful of easily-collectible biometric data in descending order of mutual information between feature and PM<sub>2.5</sub>
- paper/
  - analysis_notebook.ipynb - jupyter notebook containing code to reproduce analysis and figures used in paper
- environment.yml - file required to re-create conda environment to run analysis_notebook.ipynb
  - Clone repo and change into its directory
  - Run ```conda env create -f environment.yml``` and use the notebook

### Citation
---
If you find value in this software and would like to cite it, please use the following citation:

`Fernando, B. A., et al. DUEDARE_multiple_participants. 2023. https://github.com/mi3nts/DUEDARE_multiple_participants` 

___Bibtex___:
```
@misc{fernando2023,
  author       = {Fernando, B. A. and Talebi, S. and Wijeratne, L. O. H. and Waczak, J. and Sooriyaarachchi, V. and Lary, D. and Sadler, J. and Lary, T. and Lary, M. and Aker, A.},
  title        = {DUEDARE_multiple_participants},
  year         = {2023},
  howpublished = {[Data set](https://github.com/mi3nts/DUEDARE_multiple_participants)},
}
```
---
Data is also available at: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10152548.svg)](https://doi.org/10.5281/zenodo.10152548)

