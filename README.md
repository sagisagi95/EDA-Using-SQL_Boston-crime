**[SQL] Crime Pattern Analysis in Boston (2018).**

This project aims to explore Boston crime patterns and trends across time, location, and crime types.

#ABOUT DATASET
This large dataset contains basic information about the crime instances that occurred during 2015-2018 at Boston. Only data from Jan to Sep 2018 would be filtered later for the analysis within the project scope.

The following tables provide a summary about each column in this dataset:

- Table 1: crime.csv

| INCIDENT_NUMBER  |  text  |  Index that uniquely defines a crime/incident. 
OFFENSE_CODE  bigint  Types of crimes/incidents (defined by code) 
OFFENSE_CODE_GROUP  text  Descriptions about crime/incident types, e.g., robbery, vandalism, larceny , … 
DISTRICT  text  The districts in which crime instances occurred. 
REPORTING_AREA  int  The reporting area of a crime/incident. 
OCCURRED_ON_DATE  text  Dates of crime/incident occurrences. 
YEAR  int  Year of crime/incident occurrences. 
MONTH  int  Month of crime/incident occurrences. 
DAY_OF_WEEK  text  On what day a crime/incident occurred in a week.
HOUR  int  The hours at which a crime/incident occurred. 
UCR_PART  text  Crime categories proposed by the Uniform Crime Reporting (UCR) system, e.g., PART ONE, PART TWO, PART THREE…
STREET  text  The streets on which crime instances occurred. 
Lat  double The latitude of a crime location. 
Long  double  The longitude of a crime location.
Location  text  Latitude and longitude of a crime location.

- Table 2: offense_codes.csv

CODE  int  Unique codes of crimes/incidents 
NAME  text  Descriptions about crime/incident types

#QUESTIONS
When do crimes most frequently occur?
Where do crimes occur most often, and how are they distributed by location?
What types of crimes are most common, especially in specific times or places?

Language used: SQL
Skills used: Converting Data Types, Windows Functions, Aggregate Functions, Joins, CTE's, Temp Tables
