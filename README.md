# Biomass Estimation Using UAVSAR and Planet Data
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18608727.svg)](https://doi.org/10.5281/zenodo.18608727)

## Overview

This repository contains the ground data and analysis code supporting the manuscript currently under review:

---

## Repository Contents

### 📁 Ground_Data
- `1_46_plots_Geojson.geojson` — Ground plot locations in GeoJSON format (EPSG:32606)  
- `All_tree_data_2025.xlsx` — Tree-level measurements and plot attributes

### 📁 Code
- `biomass_estimation.py` — Python scripts for processing data, extracting features, modeling biomass, and generating figures

---

## Data Notes

- **Ground plot data** and processed datasets are openly available under **Creative Commons Attribution 4.0 International (CC-BY 4.0)** license.  
- **UAVSAR data** are publicly available from the NASA/JPL UAVSAR archive.  
- **PlanetScope imagery** was accessed under Planet’s free educational license for research purposes. The imagery cannot be redistributed; users should acquire the data independently through Planet’s educational or commercial programs.

---

## Reproducibility

To reproduce the analyses:

1. Download UAVSAR data from the NASA/JPL archive.  
2. Acquire PlanetScope imagery through a valid Planet account.  
3. Use the scripts in `/Code/` to process the data and generate results.  
4. Follow the workflow documented in the script headers.

---

## License

- **Code**: Apache License 2.0  
- **Ground Data**: Creative Commons Attribution 4.0 International (CC-BY 4.0)

---

## Citation

If you use this dataset or code, please cite:

Badola, A., et al. (2026). *Data and code for: Biomass Estimation Using UAVSAR and Planet Data*. Zenodo. https://doi.org/10.5281/zenodo.18608727

---
