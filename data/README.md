# Dataset Information

## Dataset Name

**Diabetes 130-US Hospitals for Years 1999–2008**

## Dataset Description

This project uses the **Diabetes 130-US Hospitals for Years 1999–2008** dataset for healthcare data analysis and hospital readmission analysis.

The dataset contains hospital encounter records for patients with diabetes collected from 130 US hospitals during the period **1999–2008**. It includes demographic, admission, clinical, laboratory, medication, and hospital utilization information.

The primary target variable is **`readmitted`**, which indicates whether a patient was readmitted within 30 days, after 30 days, or not readmitted.

## Dataset Source

* **Original Source:** UCI Machine Learning Repository
* **Download Source:** Kaggle
* **Dataset Period:** 1999–2008
* **Domain:** Healthcare
* **File:** `diabetic.csv`

## Dataset Purpose

The dataset will be used to:

* Assess healthcare data quality
* Identify missing and inconsistent values
* Detect duplicate records
* Validate data types and value ranges
* Develop a data-cleaning strategy
* Analyze hospital readmission patterns
* Support healthcare data visualization and analytics in later project stages

## Data Handling

The original dataset is **not included directly in this GitHub repository**. This repository contains documentation about the dataset and its handling process.

To reproduce the analysis, download the dataset from the original/public source and place the CSV file in this directory using the following filename:

```text
data/
└── diabetic.csv
```

The raw dataset should remain unchanged. Any cleaned or transformed version should be stored separately to preserve data reproducibility.

## Important Data Considerations

The dataset contains missing values represented in some fields using `?`. These values will be identified and standardized during the data-quality assessment.

Repeated `patient_nbr` values should not automatically be considered duplicate records because the same patient may have multiple hospital encounters.

The dataset is historical and covers the period from 1999 to 2008. Therefore, findings should be interpreted within the context of the data collection period and should not automatically be generalized to current healthcare settings.

## Privacy and Ethics

The dataset is publicly available and de-identified. The project will not attempt to identify individual patients or expose sensitive information.

Analysis results will be presented in an aggregated manner, and the dataset will be used only for educational and analytical purposes.



## Reproducibility

Before running future analysis scripts, ensure that the dataset has been downloaded from the appropriate public source and placed in the `data/` directory.

All data-cleaning and transformation steps will be documented so that the analysis can be reproduced consistently.
