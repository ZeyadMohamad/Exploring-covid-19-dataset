# Exploring-covid-19-dataset

## Overview
"Exploring COVID-19 Dataset" is a data analysis project focused on understanding the global impact of the COVID-19 pandemic through detailed exploration and visualization of publicly available COVID-19 datasets. This project aims to uncover insights into the spread of the virus, the distribution of cases and deaths across different countries, and temporal trends throughout the pandemic. By leveraging various data analysis and visualization techniques, this project provides a comprehensive overview of COVID-19 statistics and trends.
## Dependencies
- Python 3.x
- pandas
- matplotlib
- seaborn
- sklearn.impute

## Dataset
The dataset, `owid-covid-data.csv` contains over 67 columns, including:
- ISO_code
- Date
- Country
- total_cases
- total_death
- total_vaccinations

Unfortunately, the csv file's size was more than 25 MB, here is the link to download it:
- https://ourworldindata.org/covid-deaths
I also advice to download the csv file manually as the OWID always update the file with more records.

The dataset should be placed in the root directory of the project.

## Usage

1. Place the csv file data file in the root directory.
2. Run the script. The script will:
   - Read the data.
   - provide some information about the data
   - drop duplicate records and unnecessary columns
   - replace any missing values with a constant
   - identify outliers using IQR
   - plot countries where deaths is more than 1000000

3. Questions answered in the script:
   - How have the number of COVID-19 cases and deaths evolved over time?
   - What is the distribution of COVID-19 cases across different countries?

