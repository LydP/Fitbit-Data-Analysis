# Fitbit Data Analysis

## Introduction

This is my analysis of Divvy Fitbit data for the Google Data Analytics certificate capstone project. My certificate can be seen [here](https://www.credly.com/badges/6e51f2de-b45a-4e2e-bff1-3da04eff93de). This repository contains the SQBPRO file in which I wrote SQLite queries for the data and my analysis and conclusions in a PDF report.

## Data

The data used in this analysis can be found [here](https://www.kaggle.com/arashnic/fitbit). The download includes the following files:

```
dailyActivity_merged.csv
dailyCalories_merged.csv
dailyIntensities_merged.csv
dailySteps_merged.csv
heartrate_seconds_merged.csv
hourlyCalories_merged.csv
hourlyIntensities_merged.csv
hourlySteps_merged.csv
minuteCaloriesNarrow_merged.csv
minuteCaloriesWide_merged.csv
minuteIntensitiesNarrow_merged.csv
minuteIntensitiesWide_merged.csv
minuteMETsNarrow_merged.csv
minuteSleep_merged.csv
minuteStepsNarrow_merged.csv
minuteStepsWide_merged.csv
sleepDay_merged.csv
weightLogInfo_merged.csv
```

## Files

### fitbit_sqlite.sqbpro

I added the above CSV files as tables to a SQLite DB file using DB Browser for SQLite. ```fitbit_sqlite.sqbpro``` contains the SQLite statements I used to query this database. 

### Bellabeat_report.pdf

This is my analysis and conclusions presented in the form of a report.

### Other

The DB file mentioned above is [here](https://drive.google.com/file/d/1JMh5irBVTTiU-9isfxUSkvOTYMhT9PbK/view?usp=sharing).
