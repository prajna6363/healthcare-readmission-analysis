# Dataset Information

## Dataset Name

Diabetes 130-US Hospitals for Years 1999–2008

## Dataset Description

The Diabetes 130-US Hospitals dataset contains healthcare information related to hospital encounters involving patients with diabetes.

The dataset includes information about patient demographics, hospital admissions, diagnoses, laboratory procedures, medications, and healthcare utilization.

The dataset is used in this project to study patterns associated with hospital readmission.

## Dataset Source

**Original Source:** UCI Machine Learning Repository

**Dataset:** Diabetes 130-US Hospitals for Years 1999–2008

**Download Source:** Kaggle

The dataset was selected because it is relevant to the project's healthcare readmission analysis objective and contains a wide range of demographic, clinical, and hospital-utilization variables.

## Target Variable

The primary target variable is:

`readmitted`

It contains three categories:

| Value | Meaning |
|---|---|
| `<30` | Patient was readmitted within 30 days |
| `>30` | Patient was readmitted after 30 days |
| `NO` | Patient was not readmitted |

## Dataset Variables

The dataset contains variables related to:

- Patient demographics
- Admission information
- Hospital stay
- Diagnoses
- Procedures
- Laboratory tests
- Medications
- Healthcare utilization
- Readmission status

Examples of variables include:

- `race`
- `gender`
- `age`
- `time_in_hospital`
- `admission_type_id`
- `discharge_disposition_id`
- `admission_source_id`
- `num_lab_procedures`
- `num_procedures`
- `num_medications`
- `number_outpatient`
- `number_emergency`
- `number_inpatient`
- `number_diagnoses`
- `readmitted`

## Data Files

The project uses a cleaned version of the dataset for analysis:

`diabetic_cleaned.xlsx`

The original raw dataset is not stored in this repository unless required and permitted by the dataset's distribution terms.

## Data Preparation

The dataset is prepared for analysis through:

- Missing-value assessment
- Duplicate checking
- Data-type validation
- Categorical consistency checks
- Invalid-value checks
- Outlier review
- Feature suitability assessment

The cleaned dataset is used as the basis for the statistical analysis and predictive modeling framework.

## Data Privacy and Ethics

The dataset is publicly available and de-identified. The project does not attempt to identify individual patients.

Healthcare data is handled responsibly, with consideration given to:

- Patient privacy
- Data security
- Bias
- Fairness
- Responsible interpretation
- Ethical use of predictive models

## Reproducibility

Researchers or reviewers wishing to reproduce the project should obtain the dataset from its original public source and place the required data file in the appropriate local project directory.

The dataset source and processing decisions are documented to support reproducibility.
