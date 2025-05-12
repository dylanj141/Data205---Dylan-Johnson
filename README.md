# Data205 --- Dylan-Johnson-Capstone Project US Water Crisis
This repository contains all code, data, and documentation related to my final project for Data 205: The US Water Crisis. The project investigates national and state-level water use trends across public, thermoelectric, and irrigation sectors, evaluates sustainability thresholds, and explores efficiency through Gallons Per Capita Per Day (GPCD). The work includes modeling projections through 2100 and linking them to population trends and water quality concerns such as salinity.

Repository Contents
BKB_WaterQualityData_2020084.csv: Cleaned EPA/USGS water quality dataset focused on temperature, salinity, pH, and dissolved oxygen at water sampling sites nationwide.

Population_data.xlsx: Contains annual population counts (2000–2100) broken down by sex, origin, and race, used to estimate state-level and national per capita water use.
 
Water_Use_10States.csv: Wide-format public water use data for 10 U.S. states across multiple years.

TEWU_10States.csv: Thermoelectric water use data for the same 10 states, including water withdrawals in million gallons per day (MGD).

Irrigation.xlsx: State-level irrigation water use for the 10-state subset, used to quantify agricultural demand.

Key for CSV files.pdf: A data dictionary providing definitions for column names and codes used in the water datasets.

DJohnson_Final_Report_Data205_CRN_34665.pdf: Final report summarizing the project’s goals, methodology, results, and interpretation for both technical and general audiences.

The US Water Crisis.pptx: A visual slide deck summarizing the key findings and visualizations, used for presentation.

DylanJohnson_Data205_EDA.Rmd & EDA2.0.Rmd: R Markdown documents performing exploratory data analysis and updates with modeling components.

DylanJohnson_Data205_GraphingAndAnalysis.Rmd: Consolidated file for all major plots, projections, sustainability threshold comparisons, and GPCD calculations.

README.md: This file—providing an overview of the project structure, goals, and usage instructions.

Getting Started
To reproduce the analysis, open any of the .Rmd files in RStudio. All required packages are listed in the code chunks, and you may need to install packages like tidyverse, ggplot2, janitor, lubridate, and scales.


Links:
Census - https://www.census.gov/data/datasets/2023/demo/popproj/2023-popproj.html
USGS - https://water.usgs.gov/nwaa-data/subset-download
