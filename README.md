# Predicting Animal Shelter Outcomes

This project analyzes and predicts whether animals arriving at a shelter (dogs and cats) will be adopted or euthanized, based on multiple features and characteristics.

## Project Overview

The analysis includes:
- Data cleaning and preparation.
- Exploratory data analysis.
- Building predictive models to estimate the likelihood of adoption versus euthanasia.
- Evaluating the importance of various parameters affecting outcomes.

## Repository Contents

- **execution.Rmd**  
  The main R Markdown script for processing, analysis, and report generation.

- **file.xlsx**  
  Input dataset containing the raw information used for modeling.  
  **Important:** This file must be in the same directory as `execution.Rmd` before running the script.

- **clean_data.csv**  
  Cleaned version of the dataset after preprocessing.

- **DataReport.html**  
  Automatically generated HTML report summarizing data exploration and model results.

- **data_report_final.pdf**  
  PDF version of the final report.


## How to Run the Analysis

1. **Install R and RStudio**  
   - R version 4.x or later is recommended.

## Install Required R Packages

Before running the analysis, make sure you have the following R packages installed:

```r
install.packages(c(
  "finetune",
  "doParallel",
  "tidymodels",
  "themis",
  "vip",
  "viridis",
  "parallel",
  "RANN",
  "DMwR2",
  "readxl",
  "stringr",
  "scales",
  "dplyr",
  "pROC",
  "MLmetrics",
  "tidyverse",
  "forcats",
  "lubridate",
  "ggthemes",
  "ggridges",
  "ggplot2",
  "ggforce",
  "xgboost",
  "Matrix",
  "tictoc",
  "embed",
  "yardstick"
))
```

## Verify File Placement
Ensure that `file.xlsx` is located in the same folder as `execution.Rmd`.

## Run the Script

Open `execution.Rmd` in RStudio.

Click **Knit** to generate the HTML report.

Output file `DataReport.html` will be created automatically.

## Notes About the PDF Report

The file `data_report_final.pdf` contains the complete research documentation and is **not** generated automatically by running the script.

## Project Goals

- Identify key factors influencing animal outcomes.
- Provide insights to improve adoption rates and reduce euthanasia.
- Demonstrate the predictive performance of different machine learning models.

## Author

Roy Menashko, Shira Atia, Nadav Gonen, Ben Rahamim