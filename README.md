# Female-Brain-Health

# Project Overview
This project was conducted as part of a Kaggle competition in collaboration with the Break Through Tech AI Program. The challenge aims to analyze a dataset containing fMRI data and demographic metadata to predict ADHD diagnoses in study participants.

# Objective of the Challenge
The goal of this challenge is to build a machine learning model that accurately classifies whether an individual has ADHD based on the given features, including categorical metadata, quantitative metadata, and fMRI connectivity matrices.

# Real-World Significance and Potential Impact
ADHD diagnosis is often complex, requiring extensive clinical evaluation. If machine learning models can assist in early and more objective diagnosis, it could help:

* Reduce misdiagnoses

* Provide additional tools for clinicians

* Enhance early intervention strategies

Improve patient outcomes through tailored treatments

# Data Exploration
### Dataset(s) Used
1. The dataset consists of multiple components:

  * Categorical Metadata (10 columns, 1213 entries)

* Contains study site information, family background, and demographic data such as ethnicity.

* Notable missing data: PreInt_Demos_Fam_Child_Ethnicity column has 11 missing values.

2. Quantitative Metadata (19 columns, 1213 entries)

* Includes behavioral test scores.

* Notable missing data: MRI_Track_Age_at_Scan column has 360 missing values.

3. Connectome Metrics (19,901 columns, 1213 entries)

* fMRI-based features representing brain connectivity patterns.

4. Training Solutions (3 columns, 1213 entries)

* Contains labels for ADHD diagnosis and gender.

### Data Preprocessing and Handling Missing Values
* Quantitative data: Missing values were replaced using the median.

* Categorical data: Missing values were replaced using the mode, as the dataset had only a small number of missing values.

Exploratory Data Analysis (EDA)
Below are some visualizations that summarize the dataset:
