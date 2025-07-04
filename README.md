#[SQL] Crime Pattern Analysis in Boston (2018)

This project aims to explore Boston crime patterns and trends across time, location, and crime types.

## 📊 ABOUT DATASET

This dataset contains basic information about crime instances that occurred in **Boston** from 2015 to 2018.
Only data from **January to September 2018** will be filtered later for analysis within the project scope.

---

## 🗂️ Data Dictionary

### Table 1: `crime.csv`

| Column             | Type    | Description                                                                 |
|--------------------|---------|-----------------------------------------------------------------------------|
| `INCIDENT_NUMBER`  | text    | Index that uniquely defines a crime/incident                               |
| `OFFENSE_CODE`     | bigint  | Type of crime/incident (defined by code)                                   |
| `OFFENSE_CODE_GROUP` | text  | Description of crime type (e.g., robbery, vandalism, larceny, etc.)        |
| `DISTRICT`         | text    | District where the crime occurred                                          |
| `REPORTING_AREA`   | int     | Reporting area of the incident                                             |
| `OCCURRED_ON_DATE` | text    | Date of the crime/incident                                                 |
| `YEAR`             | int     | Year of occurrence                                                         |
| `MONTH`            | int     | Month of occurrence                                                        |
| `DAY_OF_WEEK`      | text    | Day of the week when the incident happened                                 |
| `HOUR`             | int     | Hour of occurrence                                                         |
| `UCR_PART`         | text    | Crime category based on UCR (e.g., PART ONE, PART TWO, PART THREE…)        |
| `STREET`           | text    | Street name where the incident occurred                                    |
| `Lat`              | double  | Latitude of the incident                                                   |
| `Long`             | double  | Longitude of the incident                                                  |
| `Location`         | text    | Combined latitude and longitude                                            |

---

### Table 2: `offense_codes.csv`

| Column   | Type | Description                            |
|----------|------|----------------------------------------|
| `CODE`   | int  | Unique code of crime/incident          |
| `NAME`   | text | Description of the crime/incident type |

---

## ❓ QUESTIONS TO ANSWER

1. **When** do crimes most frequently occur?
2. **Where** do crimes occur most often, and how are they distributed geographically?
3. **What types** of crimes are most common, especially in specific times or locations?

---

**Language used:** SQL

**Skills used:** Converting Data Types, Windows Functions, Aggregate Functions, Joins, CTE's, Temp Tables
