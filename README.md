# Terridev_GSG

## Description:
This repository includes code aiming at generating Sustainable Development snapshots for each country around the world by combining publicly available data and inputing directly from APIs, weblinks and through webscrapping techniques. The objective is to create a snapshot for each countrybased on 35+ indicators, allowing to rank and compare countries to their income group or regional peers and assess their performance in terms of sustainable development.

This repository includes two files in R programming language:
1) SD_profiles_dataset_code.R = file to generate the database including the 35+ indicators
2) Country_datasets_code_loop_v2.R = file to generate individual tables and graphs for each country

## Installation:
The following R packages have to be installed using the install.packages() command line:
For data extraction and data scraping: WDI, rvest, readxl
For data wrangling: plyr, dplyr, tidyverse, data.table
For data visualization: ggplot2, grid

## Usage:
1) Adjust output paths and run SD_profiles_data_code.R to generate datasets
2) Adjust input and output paths, choose regional/income group (lmics,umics,linc,hinc,MENA,LAC, etc.) for comparison and run Country_datasets_code_loop_v2.R to generate graphs

Note: do not forget to create the folder structure before running the code

## Credits:
Alex Chunet
