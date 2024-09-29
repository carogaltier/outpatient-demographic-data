# Demographic Data Processing for Hospital Outpatient Attendances

This repository contains a Jupyter Notebook designed to create a table that reflects realistic proportions of hospital outpatient attendances and non-attendances based on demographic data. The source data is from the "Outpatient attendances by age and gender 2023-24" table provided by the Hospital Episode Statistics (HES), NHS England. The reference data can be accessed [here](https://digital.nhs.uk/data-and-information/publications/statistical/hospital-outpatient-activity/2023-24).

## Overview

The purpose of this notebook is to convert raw hospital attendance data into a normalized format that can be used to create synthetic datasets for adult outpatient populations. By transforming the data into proportional values, this approach enables more realistic representations of gender and age distributions in synthetic data generation, which can be useful for modeling healthcare utilization and resource planning.

### Main Steps

1. **Data Preparation:** Load the raw data and filter out pediatric patients (those under 15 years old) to focus on adult outpatient patterns.
2. **Normalization:** Convert attendance and non-attendance counts into percentages to reflect realistic demographic distributions.
3. **Validation:** Ensure that the resulting proportions are consistent and accurately represent the total population distribution.
4. **Export:** Save the processed data into a CSV file for future use, such as synthetic data generation or further analysis.

## Applications

This notebook is particularly useful for creating synthetic datasets with proportions that mimic real-world data of adult hospital outpatients. The normalized data can serve as a foundation for various applications in healthcare analytics, policy planning, and resource allocation.

## Requirements

- Python 3.x
- pandas library
- Jupyter Notebook or Google Colab for running the notebook

## How to Use

1. Clone the repository.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Run the cells in sequential order to generate the normalized table.
4. The final processed data will be exported as a CSV file named `final_demographics.csv`.

## Data Source

The original data is sourced from the Hospital Episode Statistics (HES), NHS England. Access the data [here](https://digital.nhs.uk/data-and-information/publications/statistical/hospital-outpatient-activity/2023-24).

### Author

**María Carolina González Galtier**

- [Profile](https://github.com/carogaltier "María Carolina González Galtier")

### License
[GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/)

### 🤝 Support

Contributions, issues, and feature requests are welcome!
Give a ⭐️ if you like this project!
