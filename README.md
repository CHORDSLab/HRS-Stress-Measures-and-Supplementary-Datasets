[<img src="./docs/images/lab_logo_banner.png" alt="CHORDS Lab Logo" width="80%"/>](https://labs.wsu.edu/chords/)

# CHORDSLab / HRS-Stress-Measures-and-Supplementary-Datasets
>[labs.wsu.edu/chords](https://labs.wsu.edu/chords/)

_Last updated: September 8, 2025_

This repository contains guides and R scripts for generating analysis-ready datasets from the **Health and Retirement Study (HRS)**—including **longitudinal stress measures** and a **geographic subset** (Beale 2003/2013). Outputs are standardized to person-year and designed to join seamlessly with our [HRS Allostatic (over)Load dataset](https://github.com/CHORDSLab/Allostatic-over-Load-Repository/tree/main/HRS) via the key `id_year`.

---

## HRS Supplementary Datasets: Scope
- **Stress Measures (longitudinal):** Derived indicators and tidy person-year outputs for midlife and older adults across multiple waves (2006-2022).
- **Geographic Subset:** Cross-wave region/division & mobility file processed to Beale 2003/2013 codes for 2006–2022.

All datasets are harmonized to facilitate downstream analyses and integration with our Allostatic (over)Load pipeline.

---

## Project Team & Timeline
- Shawna Beese, Ph.D. RN  
- Jason Cross, B.S. Data Analytics   

**Timeline:** August 2025–present

---

## Key Dates
- Repository scaffolding and initial scripts drafted: August 2025  
- Initial public release: September 2025

---

## Project Objectives
- Provide clear, reproducible **data access guides** and **R Markdown pipelines** for HRS-based supplementary datasets.  
- Standardize outputs to **person-year** and a shared join key (**`id_year`**) for easy integration with the HRS Allostatic (over)Load dataset.  

---

## Protocol
Our lab’s protocol for calculating allostatic (over)load—and the broader data processing approach—is detailed in our preprint on *medRxiv*:  
**Beese S, Cross J, Rice D, & DeJong TL (2025).** *Allostatic (over)Load Measurement: Workflow and repository.*  
https://doi.org/10.1101/2025.07.31.25332519

These supplementary datasets (stress, geographic) are aligned to join with the allostatic dataset produced under that protocol.

---

## Usage
If you use these supplementary datasets, guides, or any portion of this repository in your work, please cite the repository directly:

**CHORDS Lab.** (2025). *HRS Stress Measures and Supplementary Datasets.*  
https://github.com/CHORDSLab/HRS-Stress-Measures-and-Supplementary-Datasets  

For details on the underlying protocol for calculating allostatic (over)load and constructing the primary dataset, please also cite:  
Beese S, Cross J, Rice D, & DeJong TL (2025). *Allostatic (over)Load Measurement: Workflow and repository.* https://doi.org/10.1101/2025.07.31.25332519

---

## Repository Contents
Below is an overview of the main folders in this repository, with links and brief descriptions.

| Folder | Description |
|--------|-------------|
| [`/HRS_stress`](HRS_stress/) | Scripts and guides for building the **HRS stress measures** dataset (longitudinal person-year outputs); includes `HRS_stress_access_guide.md` and `HRS_stress_dataset_construction.Rmd`. |
| [`/HRS_geographic`](HRS_geographic/) | Scripts and guides for the **HRS geographic subset** (Beale 2003/2013; waves 2006–2022); includes `HRS_geo_dataset_construction.Rmd` and `HRS_geo_access_guide.md`. |
| [`/docs`](docs/) | Project documentation, images, and internal reference materials. |


