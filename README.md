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
