# SQL Data Analysis – COVID-19

This project contains SQL queries used to analyze COVID-19 data, focusing on case fatality rates, infection rates relative to population, and vaccination trends.

## Overview
The analysis explores:
- Total COVID-19 cases versus total deaths by location
- Infection rates relative to population size
- Aggregated case and death statistics at the continent level
- Vaccination trends over time, with a focus on Canada

## Analysis Highlights
- Calculated death rates using aggregated new cases and new deaths
- Computed infection rates as a percentage of population
- Used filtering to exclude incomplete or non-country-level data
- Applied window functions to analyze cumulative vaccination trends
- Created a SQL view to store vaccination trend results for reuse

## SQL Techniques Used
- Aggregate functions (`SUM`, `ROUND`)
- Conditional filtering (`WHERE`, `HAVING`)
- Joins across multiple tables
- Window functions (`SUM() OVER (PARTITION BY ...)`)
- View creation for analytical reuse

