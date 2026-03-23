# WiDS 2024 Breast Cancer Dashboard

## Title: Breast Cancer Treatment Equity Dashboard: WiDS 2024

## Description:
This dashboard was developed to identify and visualize the socioeconomic, geographic, and clinical factors that contribute to delays in breast cancer treatment initiation. By analyzing the time from diagnosis to first treatment, this project aims to highlight systemic disparities in healthcare access and provide a data-driven narrative on health equity.

## Tech Stack:
Data Visualization: Power BI Desktop  
Data Transformation: Power Query  
Calculations & KPIs: DAX (Data Analysis Expressions)  
File Formats: .pbix (Development), .png (Previews)  

## Data Source:
The dataset was provided by Gilead Sciences for the WiDS (Women in Data Science) 2024 Datathon.
Scale: 27,000 observations.
Scope: Real-world data from 2015–2018 focusing on patients diagnosed with metastatic triple-negative breast cancer (TNBC).
Composition: Clinical records from HealthVerity enriched with third-party geodemographic data (Census-level socioeconomic indicators).

## Problem:
Metastatic TNBC is a highly aggressive form of cancer requiring urgent intervention. Delays in starting treatment directly impact patient outcomes. The core challenge was to predict the Treatment Period (days from diagnosis to first treatment) and understand why certain populations face significantly longer wait times.

## Goal of the Dashboard:
The primary goal is to move beyond simple prediction and provide a diagnostic tool for healthcare providers and policymakers to visualize disparities. It seeks to answer which social and economic factors such as income, insurance, or location create barriers to timely care.

## Key Visuals:
Overall KPIs: Provides an immediate baseline of the 70-day median treatment delay and the scale of the population (27K patients).

Treatment Trends (2015-2018): A line chart tracking the significant reduction in median treatment periods over time, providing historical context.

Insurance & Payer Impact: A bar chart revealing how different payer types, such as Medicare Advantage versus Commercial insurance, correlate with different speeds of care.

Age-Based Delays: A binned analysis showing a linear increase in treatment wait times as patients get older.

Geographic Disparity: A ranked bar chart highlighting regional differences, with the Pacific and Middle Atlantic divisions showing the highest delays.

Clinical Indicators: A horizontal bar chart showing how metastatic first treatment types (e.g., Nonsteroidals) impact the median wait time.

## Insights and Impact:
The Age Gap: Patients over the age of 70 face the longest delays, highlighting a need for better support systems for senior patients.

The Poverty Penalty: Analysis using binned socioeconomic data revealed that patients in high-poverty ZIP codes wait significantly longer for treatment (up to 92 days) compared to those in low-poverty areas (70 days).

Systemic Barriers: Insurance type is a major predictor of access; patients with Medicare Advantage face higher median wait times than those with Commercial coverage.

Impact: These insights allow organizations to identify and prioritize high-risk regions or demographic groups for targeted intervention, ensuring that the most vulnerable patients receive care within the critical clinical window.

## Screenshot/Demo: 
https://github.com/Aditirk8/WiDS_2024_Breast_Cancer_Dashboard/blob/main/Snapshot_of_Breast_Cancer_Dashboard.png

