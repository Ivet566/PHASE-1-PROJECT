# PHASE-1-PROJECT---IVET-BUYAKI
OVERVIEW

The phase 1 project entails a series of data cleaning, imputation, analysis, and visualization with an aim of generating insights for a business stakeholder.

BUSINESS UNDERSTANDING

The client intends to expand into new industries to diversify their portfolio,the main interest being purchasing and operating airplanes for commercial and private enterprises.This project aims to determine aircraft with the lowest risk for the client to start the new business endeavor.

DATA UNDERSTANDING AND ANALYSIS

The dataset,(obtained from kaggle), is from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.The link to the dataset is shown below;

https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses

The dataset is a csv file that has been imported as a pandas dataframe.Before cleaning the dataset had 88,889 rows and 31 columns.The data is constituted of columns describing the various accidents involving different types of aircrafts,the location of their happenings,the possible causes as well as the repercussions of the accidents,i.e the injuries,fatal,serious and minor.There were mixed data types within the data set as well some missing values.

During data cleaning columns such as Airport.Code,Airport.Name,Schedule were dropped as they don't have an impact on the assessment.A column like the 'Schedule' had 8803 missing values, a big number that would reduce the quantity of data for analysis if dropped.
The key columns for the analysis such as Aircraft category,Aircraft damage had their missing values/rows dropped.This is because imputing any values would affect the integrity of the findings.The other key numerical columns missing values such as total fatal injuries,total serious injuries and total minor injuries were imputed with their mean values.The standard deviation of the values was very low, indicating most of the values were clustered around the mean.After cleaning the rows came to 10,011 rows and 25 columns.

On further analysis;
1) The airplanes are the most common aircraft in that market,reaching a count of 8412.They are followed from a far by the helicopters, then the weight-shift.

![image](https://github.com/user-attachments/assets/5a4e7840-59ea-411b-ac9a-b2408098c0e0)


2)From the above aircraft categories graph below,it can be seen that blimp had only minor injuries,though the number was quite high compared to the other aircraft.
The glider is seen to have the lowest number of fatal,serious and minor injuries combined, followed by the airplane.
Ballon appears to have the highest number of engines as well as highest number of serious injuries.

![image](https://github.com/user-attachments/assets/00d7e0d4-2aea-4a5a-81c7-2cedc6d4938d)


3)The sums graph shows that cumulatively the total number of fatal,serious and minor injuries over the given duration is the highest.Its followed by the helicopter.

![image](https://github.com/user-attachments/assets/ab12336a-80a4-485f-a5b0-cf363906075a)

CONCLUSION

This analysis leads to the following insights and recommendations;

INSIGHTS

-The airplane is the most commonly used aircraft from the presented data set, followed by the helicopter.
 -The average rate of occurrence/ mean of accidents of the airplane is almost at the same range as the other fewer planes.The three lowest are the glider,airplane and helicopter.
 -A lot of accidents occurred when the Visual Meteorological condition was in place.
 -The reciprocating engine type is the most common.

 RECOMMENDATIONS

 -The three lowest risk aircraft are the airplane,helicopter and glider.The client should consider the three options when evaluating the lowest risk aircraft.
 
-Further analysis and data be provided on the relation between the Visual Meteorological condition and accidents.Instrument Meteorological conditions seem to be a safer option.

-Further research be done on the relation between the Engine type and accident occurrence.

The interactive dashboard is in this link, https://public.tableau.com/authoring/AVIATIONACCIDENTDATA/Story1#1.










# PHASE---PROJECT-IVET-BUYAKI
