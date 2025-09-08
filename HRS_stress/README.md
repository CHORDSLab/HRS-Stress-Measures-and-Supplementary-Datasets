# HRS_stress
*CHORDS Lab – Washington State University*  

_Last updated: [2025-08-30]_  

## Contents  

- [`HRS_stress_access_guide.md`](HRS_stress_access_guide.md)  
  Instructions for accessing and downloading raw stress data from the [Health and Retirement Study (HRS)](https://hrs.isr.umich.edu/).

- [`HRS_stress_dataset_construction.Rmd`](HRS_dataset_construction.Rmd)  
  R Markdown script that compiles and processes HRS stress data across multiple waves (2006–2022). The resulting supplementary stress dataset may be joined with the HRS Allostatic (over)Load dataset built in `HRS_dataset_construction.Rmd`, using the common key `id_year`.  

- [`HRS_stress_data_dictionary.xlsx`](HRS_stress_data_dictionary.xlsx)  
  An Excel workbook with a comprehensive mapping of stress-related measures across HRS survey waves (2006–2022).  
  The dictionary includes:  
  - **Standardized CHORDS variable names** (e.g., `eomfs`, `ocs_01–08`, `pss_01–10`, `sle_01–12`)  
  - **Original HRS survey variable codes** by wave  
  - **Metadata** (datatype, derived status, coding notes) to support harmonized analysis  


