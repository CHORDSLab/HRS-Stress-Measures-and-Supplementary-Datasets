<img src="images/hrs_logo.png" alt="HRS" width="40%"/> 

# HRS Geographic Data Access Guide  
*CHORDS Lab – Washington State University*

_Last updated: [2025-08-30]_

This guide walks through the process of downloading the raw HRS geographic data needed to run `HRS_geo_dataset_construction.Rmd` and build a supplementary geographic dataset for allostatic (over)load research using data from the [Health and Retirement Study (HRS)](https://hrs.isr.umich.edu/).

---

## 📁 Final Folder Structure (Preview)

Once you've downloaded and extracted the required file, your local directory should resemble the following:

    HRS Data Products/  
    ├── HRSXRegion2022v10Early  

---

## 1. Account Setup & Data Access Permissions

Before downloading, you'll need to:

1. Create an account at the [HRS website](https://hrs.isr.umich.edu/).

<img src="images/step01_account.png" alt="Create HRS Account" width="80%"/> 


## 2. Download HRSXRegion Data

Visit the [HRS Public Survey Data](https://hrsdata.isr.umich.edu/data-products/public-survey-data) page and download the **Cross-Wave Census Region/Division and Mobility File**.

<img src="images/step02a_geo_data.png" alt="Download HRS Geo Data - 2a" width="80%"/>  

<br>

<img src="images/step02b_geo_data.png" alt="Download HRS Geo Data - 2b" width="80%"/> 

#### Alternatively, you may use the following direct link to download the `Cross-Wave Census Region/Division and Mobility File`:
- [HRSXRegion2022v10Early.zip](https://hrsdata.isr.umich.edu/data-file-download/28235)

---

### Unzipping HRS Geographic Data

- Create a folder called `HRS Data Products/`
- Unzip `HRSXRegion2022v10Early.zip` into your `HRS Data Products/` directory.
- Remember the path — you’ll point to this location in `HRS_geo_dataset_construction.Rmd`.

💡 _Need help unzipping multiple files at once?_ Try [7-Zip](https://www.7-zip.org/) (Windows) or [The Unarchiver](https://theunarchiver.com/) (Mac) for batch extraction.

---

## ✅ Setup Complete -- Proceed to Geographic Subset Construction

Once the data is downloaded and extracted, run the [`HRS_geo_dataset_construction.Rmd`](HRS_geo_dataset_construction.Rmd) script in `HRS_geographic\`. This will generate the supplementary geographic dataset.

If you encounter issues or need assistance with data access or permissions, contact the [HRS Help Desk](https://hrs.isr.umich.edu/help).




