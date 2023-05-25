# Homelessness Analysis

# Authors
Stephen Yang

# Description
This project tries to determine trends in homelessness in cities around America to determine if market, socioeconomic, and other factors can predict trends in homelessness.

## Data

Data was gathered from the U.S. Department of Housing and Urban Development, or HUD. It was originally from a HUD report made in 2019 about predictors of Homelessness, which can be found here: https://www.huduser.gov/portal/sites/default/files/pdf/Market-Predictors-of-Homelessness.pdf

The data was extracted with help from Dr. Brian Fischer. It can be located at /data/05b_analysis_file_update.csv. A description file is located at /data/HUD TO3 - 05b Analysis File - Data - Dictionary.csv.

## Data Preparation
Data was prepared by subselecting a specific year of the data and taking out additional null values.

The data preparation was done using the file /Data_prep/Homelessness_Data_Preparation.ipynb. The cleaned data file is located at /Data_prep/homelessness_clean.csv.

## Analysis
A few models were made using Ridge, Lasso, and XGBoost regularization to determine the most important factors.

The analysis was done using the file /Analysis/Homelessness_Analysis.ipynb.

# License
All datasets in this repository, including cleaned datasets, are free to use. All notebooks in this repository are also free to view and modify.
