# Deliverable02-Cleaning-and-formatting

## International Mathematical Olympiad (IMO) Data Analysis: Data Cleaning and Formatting

This repository contains the cleaned and formatted data for the International Mathematical Olympiad (IMO) Data Analysis project, building upon the raw data collected in [Deliverable01-Collecting-raw-data](https://github.com/Zhongyuelin/Deliverable01-Collecting-raw-data-).

### Project Overview

This project focuses on cleaning and formatting the IMO data to prepare it for further analysis. We address issues such as missing values, outliers, inconsistent data types, and standardize variable names across the datasets.

### Data Files

The cleaned and formatted data is located in the `DataCleanAndFormatted` folder within this repository. It consists of the following files:

1. `cleaned_country_results.csv` and `formatted_country_results.rds`: Cleaned and formatted country-level results for each IMO.
2. `cleaned_individual_results.csv` and `formatted_individual_results.rds`: Cleaned and formatted individual participant results.
3. `cleaned_timeline.csv` and `formatted_timeline.rds`: Cleaned and formatted historical information about each IMO event.

### Data Cleaning and Formatting Process

The data cleaning and formatting process is documented in detail in the `IMO_data_cleaning_and_formatting.qmd` Quarto document. This process includes:

1. Handling missing values
2. Removing duplicate entries
3. Addressing outliers in score columns
4. Ensuring correct data types for all columns
5. Standardizing variable names
6. Ensuring date format consistency
7. Performing data consistency checks

### Repository Structure

- `IMO_raw_data/`: Contains the original raw data files
- `DataCleanAndFormatted/`: Contains the cleaned and formatted CSV and RDS files
- `IMO_data_cleaning_and_formatting.qmd`: Quarto document detailing the cleaning and formatting process
- `IMO_data_cleaning_and_formatting.html`: Rendered HTML report of the cleaning and formatting process

### How to Use

1. Clone this repository to your local machine.
2. Open and run the `IMO_data_cleaning_and_formatting.qmd` file to see the detailed cleaning and formatting process.
3. The cleaned and formatted data files in the `DataCleanAndFormatted/` folder are ready for further analysis.

### Dependencies

- R (version 4.0.0 or higher)
- tidyverse
- lubridate
- knitr

### Original Data Source

The original data was obtained from the TidyTuesday project, week 39 dataset of 2024. It comes from the International Mathematical Olympiad official records, scraped from https://www.imo-official.org/.

### Data Range

The dataset covers IMO events from 1959 to 2024.

### Next Steps

This cleaned and formatted dataset is now ready for in-depth analysis, including:

- Exploring historical trends in mathematics education
- Analyzing gender representation in high-level mathematics competitions
- Comparing international education systems
- Studying team dynamics and performance
- Investigating geographical and cultural factors influencing IMO participation and performance

### Contact

For any questions or feedback regarding this data cleaning and formatting process, please open an issue in this repository.