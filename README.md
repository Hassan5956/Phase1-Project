Aviation Accident Analysis

Overview

This repository contains a Phase 1 data science project that analyzes the National Transportation Safety Board (NTSB) aviation accident dataset (1962–2023) to identify low-risk aircraft and conditions for business expansion into aviation operations.

Business Understanding

Goal: Determine the lowest-risk aircraft types and operational conditions to guide the company's investment and operational strategy.

Stakeholder: Head of the Aviation Division

Key Questions:

What are the most common causes of aviation accidents?

Which U.S. states report the highest number of aviation accidents?

How do weather conditions affect the number and severity of fatal injuries?

Data Understanding and Analysis

Data Source

Dataset: NTSB Aviation Accident Dataset (1962–2023)

Columns: Accident summaries, injury counts, weather conditions, locations, aircraft types, flight purposes

Data Preparation

Removed missing or irrelevant entries

Converted date and numeric fields to appropriate types

Standardized categorical variables (e.g., weather conditions, state names)

Focused analysis on fatalities, state occurrences, and weather-related factors

Key Visualizations

States with Most AccidentsInsight: California, Texas, and Florida report the highest number of accidents, likely reflecting flight volume and regional activity.

Fatal Injuries by Weather ConditionInsight: Instrument Meteorological Conditions (IMC) are associated with the greatest number of fatal injuries, indicating higher risk in poor weather.

Common Causes of AccidentsInsight: Pilot error, engine failure, and controlled flight into terrain are the leading contributors to accidents.

Conclusion

Based on the analysis, we recommend:

Avoiding operations under IMC conditions to reduce fatality risk.

Prioritizing aircraft models with modern avionics and strong safety records.

Limiting initial operations to lower-risk states with favorable weather patterns.

These insights will help the aviation division make data-driven decisions on aircraft acquisition and operational planning.

