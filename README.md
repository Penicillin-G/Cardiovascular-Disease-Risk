# Cardiovascular Risk Data Analysis

# Overview

This project explores cardiovascular health data to investigate the relationship between various health, lifestyle, and demographic factors and a history of heart attack among survey respondents.

Using Python, the project performs exploratory data analysis (EDA), statistical comparisons, and data visualization to identify patterns and associations within the dataset.

# Objectives

* Explore and understand the cardiovascular health dataset.
* Examine the distribution of heart attack history among respondents.
* Investigate associations between heart attack history and selected cardiovascular risk factors.
* Visualize patterns using charts and statistical summaries.
* Identify variables that may be relevant for future heart attack prediction modeling.

## Dataset

**File:** `heart_2022_no_nans.csv`

The dataset contains health-related survey responses, including demographic characteristics, medical history, lifestyle habits, and health indicators.

The primary outcome of interest is `HadHeartAttack`, which records whether a respondent reports having had a heart attack.

Credit: Kaggle Database

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Analysis Performed

* Dataset exploration and descriptive statistics
* Missing-value and duplicate checks
* Distribution analysis of cardiovascular risk factors
* Heart attack history distribution visualization
* Crosstabulation of heart attack history against selected variables, including smoking, diabetes, angina, stroke, kidney disease, age, BMI, physical activity, and other health indicators
* Group-based heart attack rate comparisons
* Correlation analysis and heatmap visualization

## Project Structure

```text
cardiovascular-risk-data-analysis/
├── cardio_data_analysis.py
├── heart_2022_no_nans.csv
└── README.md
```

## How to Run

1. Clone or download this repository.
2. Ensure Python is installed.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

4. Run the analysis script:

```bash
python cardio_data_analysis.py
```

Ensure that `heart_2022_no_nans.csv` is in the same directory as the Python script.

## Important Note

This project is an exploratory analysis of survey data. Observed associations do not establish causation, and the analysis is not intended for clinical diagnosis or individual medical decision-making.

## Future Work

A separate project will use the same dataset to develop and evaluate a neural network for predicting reported heart attack history.

## Author

Daniel Glorious Oziomachukwu

