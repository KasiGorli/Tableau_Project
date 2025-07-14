# Tableau_Project
# Outpatient Clinic Performance Dashboard

A real-world **healthcare analytics project** built using **Tableau Prep** and **Tableau Public**, focused on analyzing outpatient clinic performance, provider efficiency, and patient satisfaction. This end-to-end project demonstrates advanced data preparation techniques, metric design, and dashboard storytelling—ideal for data analyst portfolios in healthcare.

---

##  Project Overview

This project simulates and analyzes visit-level data from outpatient clinics across multiple providers. The goal is to help healthcare administrators make informed decisions using metrics like **no-show rates**, **wait times**, **visit volumes**, and **patient satisfaction scores**.

---

##  Folder Structure

```plaintext
outpatient-clinic-performance-dashboard/
│
├── data/
│   ├── clinic_data_part1.csv          # Visit records (part 1)
│   ├── clinic_data_part2.csv          # Visit records (part 2 for union)
│   ├── provider_data.csv              # Provider specialties and metadata
│   └── survey_data.csv                # Satisfaction survey scores
│
├── flow/
│   └── clinic_performance_flow.tfl    # Tableau Prep flow
│
├── output/
│   └── cleaned_clinic_data.csv        # Final aggregated output

```

## Tools Used

**Tableau Prep

Data cleaning (splits, renaming, grouping)

Union of datasets

Joins with provider and survey data

Pivots on survey categories

Aggregation by Clinic, Provider, and Week

Simulated FIXED LOD-style calculations

Tableau Public

Multi-page dashboard

KPIs, time-series, heatmaps, and benchmarks**

Dashboard filters and user interactivity
---
## Key Metrics
Visit Count (weekly, per provider and clinic)

Average Wait Time

No-show Count & No-show %

Average Visit Duration

Patient Satisfaction Scores

Category-wise Satisfaction (Communication, Cleanliness, etc.)

Clinic-level vs Provider-level Benchmarking
---
## Dashboards Included
Clinic Weekly Overview
Trends in volume, wait time, and no-show rate

Provider Comparison
Satisfaction, no-show count, and specialty performance

Satisfaction Analysis
Donut charts and stacked bars on patient feedback

Action Center (LOD Benchmarking)
Compare provider no-show % with clinic average
---
## Tableau Prep Highlights
 Data Cleaning: Field renaming, type conversion, split values

 Transformation: Create flags, case conversion, calculated fields

 Pivots: Convert survey scores into analyzable categories

 Aggregations: Group by week, provider, clinic

 LOD-style Aggregation: Simulated FIXED [Clinic] level joins

 Final Output for Tableau Public
---
## Project Purpose
This project is designed for:

Practicing Tableau Prep’s full workflow capabilities

Publishing clean, professional dashboards using real-world healthcare metrics

Demonstrating portfolio-ready work with documentation, code, and visuals
