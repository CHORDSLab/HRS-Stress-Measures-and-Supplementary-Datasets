<img src="../images/hrs_logo.png" alt="HRS" width="40%"/> 

# HRS Stress Data Access Guide  
*CHORDS Lab – Washington State University*

_Last updated: [2025-08-30]_

This guide walks through the process of downloading and organizing the raw HRS stress data needed to run `HRS_stress_dataset_construction.Rmd` and build a supplementary stress dataset for allostatic (over)load research using data from the [Health and Retirement Study (HRS)](https://hrs.isr.umich.edu/).

---

## 📁 Final Folder Structure (Preview)

Once you've downloaded and extracted the required files, your local directory should resemble the following:

    HRS Data Products/  
    ├── HRS Core Data/  
    │ ├── h06core/  
    │ ├── h08core/  
    │ ├── h10core/  
    │ ├── h12core/  
    │ ├── h14core/  
    │ └── h16core/  
    │ └── h18core/
    │ └── h20core/
    │ └── h22core/
      

---

## 1. Account Setup & Data Access Permissions

Before downloading, you'll need to:

1. Create an account at the [HRS website](https://hrs.isr.umich.edu/).

<img src="../images/step01_account.png" alt="Create HRS Account" width="80%"/> 


## 2. Download HRS Core Data

Visit the [HRS Public Survey Data](https://hrsdata.isr.umich.edu/data-products/public-survey-data) page and download the **Core Distribution Sets** for years 2006-2022.

<img src="../images/step02a_core_data.png" alt="Download HRS Core Data - 2a" width="80%"/>  

<br>


Click the **HRS Core** link for each year (2006-2022).

<img src="../images/step02b_core_data.png" alt="Download HRS Core Data - 2b" width="80%"/>   

<br>


Download the **Distribution Set** for each year (2006-2022).

<img src="../images/step02c_core_data.png" alt="Download HRS Core Data - 2c" width="80%"/>  


#### Alternatively, you may use the following direct links to download each `HRS Core` distribution set:
- [2006 HRS Core](https://hrsdata.isr.umich.edu/data-file-download/9482)
- [2008 HRS Core](https://hrsdata.isr.umich.edu/data-file-download/5435)
- [2010 HRS Core](https://hrsdata.isr.umich.edu/data-file-download/9465)
- [2012 HRS Core](https://hrsdata.isr.umich.edu/data-file-download/5446)
- [2014 HRS Core](https://hrsdata.isr.umich.edu/data-file-download/5448)
- [2016 HRS Core](https://hrsdata.isr.umich.edu/data-file-download/14963)  
- [2018 HRS Core](https://hrsdata.isr.umich.edu/data-file-download/14964)  
- [2020 HRS Core](https://hrsdata.isr.umich.edu/data-file-download/18721)  
- [2022 HRS Core](https://hrsdata.isr.umich.edu/data-file-download/26115)  

---

### Unzipping HRS Core Data

**Setup Instructions:**
- Create a folder called `HRS Core Data/`
- Unzip each file into its own subfolder inside that directory (`h06core/`, `h08core/`, etc.)
- Each `.zip` file may contain nested `.zip` files—be sure to unzip those as well. If you're using a batch extractor, this will be handled automatically, but double-check that all subfolders are extracted

💡 _Need help unzipping multiple files at once?_ Try [7-Zip](https://www.7-zip.org/) (Windows) or [The Unarchiver](https://theunarchiver.com/) (Mac) for batch extraction.

---

## ✅ Setup Complete -- Proceed to Stress Subset Construction

<br>

Once your data is downloaded and organized, run the `HRS_stress_dataset_construction.Rmd` script in `/HRS/HRS_stress_subset/`. This will generate the supplementary geographic dataset.

If you encounter issues or need assistance with data access or permissions, contact the [HRS Help Desk](https://hrs.isr.umich.edu/help).

---



