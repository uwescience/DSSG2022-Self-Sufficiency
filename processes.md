---
layout: page
title: Processes
---

## Data
The Self-Sufficiency Standard data includes 147 files in Excel file format (xlsx, xlsb) by state and year. Each file lists counties with family types and related costs, such as housing, child care, and food costs. Most columns are consistent across files, but a few columns that contain extra information are present in specific files. For example, broadband and cell phone costs are only included in 6 files.

## Data Preparation
To store data from all the files in one database, we pre-processed the files to standardize the column names. We utilized Python packages such as Pandas and NumPy to read the data from the Excel files and to conduct data cleaning.

<img src="{{ site.url }}{{ site.baseurl }}/assets/img/pre-processing.png">

*Figure 1: Pre-processing of the Self-Sufficiency Database*
