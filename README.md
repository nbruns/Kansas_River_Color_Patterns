# Scripts for "Flow-dependent color patches in a Great Plains river"

These scripts accompany the following publication:

**Bruns, Nicholas, Gardner, John R., Doyle, Martin. 2024.**  
*"Flow-dependent color patches in a Great Plains river."*  
*Journal of Geophysical Research: Biogeosciences.*  

The dataset associated with this publication is available on Figshare:  

[10.6084/m9.figshare.26121148](https://doi.org/10.6084/m9.figshare.26125843.v1).

---

## Overview of Scripts  

The scripts perform two primary tasks:

### **1. Data Preparation**
   - **`1a_obtain_and_prepare_MS_data.R`**  
     - Retrieves and processes datasets from public data sources.  
     - Provides data provenance documentation.  
     - Calls: **`1b_helper_make_color_sensor_matchups.R`**  
   - **`1b_helper_make_color_sensor_matchups.R`**  
     - Helper script that combines sattelite and in-situ sensor data.

### **2. Manuscript Analysis & Figure Generation**
   - **`2a_make_MS_figs.Rmd`**  
     - Generates manuscript figures based on processed data.  
     - Calls: **`2b_prep_MS_paper_data.R`**  
   - **`2b_prep_MS_paper_data.R`**  
     - Prepares datasets for manuscript analysis.

---

## Data Availability  

All necessary datasets for these scripts can be accessed at:  
[10.6084/m9.figshare.26121148](https://doi.org/10.6084/m9.figshare.26121148).

---

## Citation  

If using these scripts, please cite the original publication:  

**Bruns, Nicholas, Gardner, John R., Doyle, Martin. 2024.**  
*"Flow-dependent color patches in a Great Plains river."*  
*Journal of Geophysical Research: Biogeosciences.*  
[DOI link to article, if available]

