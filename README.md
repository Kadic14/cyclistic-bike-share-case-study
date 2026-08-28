# Cyclistic Bike-Share Case Study

## Project Overview

This case study analyzes Cyclistic bike-share data to understand how casual riders and annual members use the service differently. The goal is to identify key riding patterns and provide data-driven recommendations that could help Cyclistic convert casual riders into annual members.

## Business Task

Cyclistic wants to increase the number of annual memberships. This analysis addresses the following question:

**How do annual members and casual riders use Cyclistic bikes differently?**

The findings from this analysis are used to develop recommendations for a marketing strategy focused on converting casual riders into annual members.

## Tools Used

- Google Sheets
- Pivot Tables
- Data Cleaning and Transformation
- Data Visualization
- GitHub

## Data Source

The analysis uses Cyclistic/Divvy bike-share trip data from Q1 2019 and Q1 2020. The datasets contain information about individual bike rides, including ride start and end times, rider type, and station information.

For consistency across the two datasets, rider categories were standardized:
- Customer → Casual
- Subscriber → Member

## Data Cleaning & Preparation

The datasets were prepared and analyzed in Google Sheets.

The following steps were performed:

- Created copies of the original datasets before cleaning.
- Reviewed the data for errors, missing values, and inconsistencies.
- Standardized column names between the 2019 and 2020 datasets.
- Standardized rider classifications to `casual` and `member`.
- Created a `ride_length` field by calculating the difference between the ride end time and start time.
- Created a `day_of_week` field using the ride start date, where 1 = Sunday and 7 = Saturday.
- Reviewed unusually long ride durations as potential data-quality issues.
- Created pivot tables to compare ride counts and average ride duration by rider type and day of the week.
- Analyzed Q1 2019 and Q1 2020 separately and created a combined summary of the results.
