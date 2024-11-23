# Chronic Kidney Disease (CKD) Classification Project

## Overview

This project focuses on the early-stage classification of Chronic Kidney Disease (CKD) based on medical attributes collected from patients in India. The dataset used in this project contains critical indicators related to kidney function and overall health, enabling the development of a model to classify individuals into CKD or non-CKD categories.

## Dataset Information

### Source
- **Contributors**:  
  - Dr. P. Soundarapandian (Senior Consultant Nephrologist, Apollo Hospitals, Tamilnadu, India)  
  - L. Jerlin Rubini (Research Scholar, Alagappa University)  
  - Guided by Dr. P. Eswaran (Assistant Professor, Alagappa University)  
- **Date**: July 2015  

### Summary
- **Number of Instances**: 400  
  - 250 classified as CKD  
  - 150 classified as not CKD  
- **Number of Attributes**: 25 (24 features + 1 target class)  
- **Attribute Types**:  
  - 11 numerical  
  - 14 nominal  
- **Missing Values**: Present (denoted by "?")  

### Class Distribution
- `ckd`: 250 instances  
- `notckd`: 150 instances  

## Attributes Description

The dataset includes the following attributes:

| Attribute               | Type      | Description                             |
|-------------------------|-----------|-----------------------------------------|
| Age                    | Numerical | Patient's age (years)                  |
| Blood Pressure (bp)    | Numerical | Blood pressure (mm/Hg)                 |
| Specific Gravity (sg)  | Nominal   | Urine specific gravity (1.005–1.025)   |
| Albumin (al)           | Nominal   | Protein levels in urine (0–5)          |
| Sugar (su)             | Nominal   | Sugar levels in urine (0–5)            |
| Red Blood Cells (rbc)  | Nominal   | Normal or abnormal                     |
| Pus Cell (pc)          | Nominal   | Normal or abnormal                     |
| Pus Cell Clumps (pcc)  | Nominal   | Present or not present                 |
| Bacteria (ba)          | Nominal   | Present or not present                 |
| Blood Glucose Random (bgr) | Numerical | Blood glucose (mg/dL)              |
| Blood Urea (bu)        | Numerical | Blood urea (mg/dL)                     |
| Serum Creatinine (sc)  | Numerical | Serum creatinine (mg/dL)               |
| Sodium (sod)           | Numerical | Sodium levels (mEq/L)                  |
| Potassium (pot)        | Numerical | Potassium levels (mEq/L)               |
| Hemoglobin (hemo)      | Numerical | Hemoglobin levels (gms)                |
| Packed Cell Volume (pcv)| Numerical | Packed cell volume                     |
| White Blood Cell Count (wc)| Numerical | White blood cells (cells/cumm)     |
| Red Blood Cell Count (rc)| Numerical | Red blood cells (millions/cmm)      |
| Hypertension (htn)     | Nominal   | Yes or no                              |
| Diabetes Mellitus (dm) | Nominal   | Yes or no                              |
| Coronary Artery Disease (cad) | Nominal | Yes or no                          |
| Appetite (appet)       | Nominal   | Good or poor                           |
| Pedal Edema (pe)       | Nominal   | Yes or no                              |
| Anemia (ane)           | Nominal   | Yes or no                              |
| Class                  | Nominal   | CKD or not CKD                         |

## Goals

- Develop a classification model to identify CKD status.  
- Analyze the impact of various medical indicators on kidney health.  
- Handle missing data effectively for robust model performance.  

## Usage

1. Preprocess the data by addressing missing values and standardizing numerical attributes.  
2. Train a classification model using machine learning algorithms.  
3. Evaluate the model using metrics such as accuracy, precision, recall, and F1 score.  

## Citation

Please cite the contributors if you use this dataset:  
**Dr. P. Soundarapandian, L. Jerlin Rubini, and Dr. P. Eswaran**. For inquiries, contact:  
- **L. Jerlin Rubini** (Email: jel.jerlin@gmail.com)  
- **Dr. P. Eswaran** (Email: eswaranperumal@gmail.com)  
