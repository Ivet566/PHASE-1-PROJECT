# PHASE-1-PROJECT---IVET-BUYAKI
OVERVIEW

The phase 1 project entails a series of data cleaning, imputation, analysis, and visualization with an aim of generating insights for a business stakeholder.

BUSINESS UNDERSTANDING

The client intends to expand into new industries to diversify their portfolio,the main interest being purchasing and operating airplanes for commercial and private enterprises.This project aims to determine aircraft with the lowest risk for the client to start this new business endeavor.

DATA UNDERSTANDING AND ANALYSIS

The dataset,(obtained from kaggle), is from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.The link to the dataset is shown below;

https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses

The dataset is a csv file that has been imported as pandas dataframe.Before cleaning the dataset had 88,889 rows and 31 columns.The data is constituted of columns describing the various accidents involving different types of aircrafts,the location of their happenings,the possible causes as well as the repercussions of the accidents,i.e the injuries,fatal,serious and minor.There were mixed data types within the data set as well some missing values.

During data cleaning columns such as Airport.Code,Airport.Name,Schedule were dropped as they don't have an impact on the assessment.A column like the 'Schedule' had 8803 missing values, a big number that would reduce the data for analysis if dropped.
The key columns for the analysis such as Aircraft category,Aircraft damage had their missing values/rows dropped.This is because imputing any values would affect the integrity of the findings.The other key numerical columns missing values such as total fatal injuries,total serious injuries and total minor injuries were imputed with their mean values.This is because the standard deviation of the values was very low, indicating most of the values were clustered around the mean.



