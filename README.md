# Time-Series Data Pipeline for Operational Monitoring

## Overview
This project demonstrates a simple end-to-end data engineering pipeline
for processing time-series operational data using Python and SQL.

## Problem
Operational data often contains inconsistent formats and corrupted values,
making it unreliable for monitoring and decision-making.

## Pipeline
1. Load raw CSV time-series data
2. Validate data types and handle corrupted numeric values
3. Clean and sort records chronologically
4. Apply time-series transformations (rolling average, daily change)
5. Store processed data into a relational database (SQLite)
6. Query data using SQL for operational insights

## Tools
- Python (Pandas)
- SQLite
- Google Colab

## Outcome
The final dataset is clean, validated, and structured for reliable
time-series analysis and operational monitoring.
