# HRS_stress
*CHORDS Lab – Washington State University*  

_Last updated: [2025-10-29]_  

## Contents  

- [`HRS_stress_access_guide.md`](HRS_stress_access_guide.md)  
  Instructions for accessing and downloading raw stress data from the [Health and Retirement Study (HRS)](https://hrs.isr.umich.edu/).

- [`HRS_stress_dataset_construction.Rmd`](HRS_dataset_construction.Rmd)  
  R Markdown script that compiles and processes HRS stress data across multiple waves (2006–2022). The resulting supplementary stress dataset may be joined with the HRS Allostatic (over)Load dataset built in `HRS_dataset_construction.Rmd`, using the common key `id_year`.  

- [`HRS_stress_data_overview.pdf`](HRS_stress_data_overview.pdf)  
  A summary document describing the origins, variables, and structure of the HRS Stress Dataset.  
  Includes:  
  - Background on the Health and Retirement Study and the Leave-Behind Psychosocial Questionnaire (LBQ)
  - Variable categories and definitions (financial strain, chronic stressors, perceived stress, and life events)
  - [Table 1: HRS Stress Measures by Category and Survey Year](images/hrs_stress_tbl.png)  
  - Notes on variable availability and harmonization across waves

- [`HRS_stress_data_dictionary.xlsx`](HRS_stress_data_dictionary.xlsx)  
  An Excel workbook with a comprehensive mapping of stress-related measures across HRS survey waves (2006–2022).  
  The dictionary includes:  
  - **Standardized CHORDS variable names** (e.g., `eomfs`, `ocs_01–08`, `pss_01–10`, `sle_01–12`)  
  - **Original HRS survey variable codes** by wave  
  - **Metadata** (datatype, derived status, coding notes) to support harmonized analysis  


