# HealthConnect – Advanced Analytics & Decision Support

## Overview

This project is part of the HealthConnect Experience Lab, focused on improving patient appointment attendance and healthcare support using data and AI.

Building on the Week 5 Appointment Attendance & No-Show Analysis, Week 6 focused on deeper analysis of the factors associated with patient no-shows and how these factors interact.

The goal was to move from identifying patterns to generating more actionable insights that can support healthcare decision-making and future predictive modelling.

## Week 6 Objectives

- Investigate the most important Week 5 findings in greater depth.
- Examine relationships between patient and appointment characteristics.
- Validate key Week 5 KPIs.
- Identify high-impact attendance risk patterns.
- Translate analytical findings into practical actions.
- Provide relevant findings to the Data Science track for modelling decisions.
- Improve the existing Power BI dashboard with additional analytical views.

## Advanced Analysis

### 1. Previous No-Shows × Reminder Status

Patients with previous no-shows generally recorded higher no-show rates.

The analysis also showed that patients who received reminders generally had lower no-show rates within the same previous-no-show groups.

For example:

- 2 previous no-shows + no reminder: 66.67% no-show rate
- 2 previous no-shows + reminder: 56.51% no-show rate

This suggests that reminder interventions may be particularly relevant for patients with a history of missed appointments.

### 2. Booking Lead Time × Previous No-Shows

No-show rates increased substantially as appointments were booked further in advance.

Overall no-show rates across the booking lead-time groups were:

- 0–15 days: 30.60%
- >15–30 days: 43.04%
- >30–45 days: 52.82%
- >45–60 days: 67.16%
- 60+ days: 68.09%

The analysis also showed higher no-show rates among patients with previous no-shows.

This highlights long booking lead time and previous no-show history as important factors for attendance-support strategies.

### 3. Distance × Previous No-Shows × Reminder Status

Distance to the clinic was further examined alongside previous no-show history and reminder status.

Higher distance bands generally showed higher no-show rates, although some fluctuations occurred across groups.

Reminder recipients recorded lower or similar no-show rates across several distance groups.

Distance therefore provides an additional risk indicator that can be considered when prioritising attendance-support interventions.

## Key Findings

The Week 6 analysis identified four important factors:

1. **Previous no-shows** – strong indicator of attendance risk.
2. **Booking lead time** – longer lead times are associated with higher no-show rates.
3. **Distance to clinic** – greater distance generally corresponds with higher no-show rates.
4. **Reminder status** – reminders are associated with lower no-show rates across several risk groups.

## Business Recommendations

Based on the deeper analysis:

- Prioritise patients with previous no-shows for targeted reminders and confirmation.
- Provide additional confirmation closer to appointments booked far in advance.
- Consider distance when prioritising attendance-support interventions.
- Explore easier rescheduling and confirmation processes for higher-risk patients.
- Use these findings to support future predictive modelling of appointment no-shows.

## Dashboard Enhancement

The original Week 5 Power BI dashboard was retained.

A dedicated Week 6 analysis page was added to present deeper analytical views, including:

- Previous No-Shows × Reminder Status
- Booking Lead Time × Previous No-Shows
- Distance × Previous No-Shows × Reminder Status

This preserves the original Week 5 dashboard while providing a dedicated space for advanced analysis.

## Cross-Track Integration

The Data Analytics findings were prepared as an analytical handoff to the Data Science track.

The handoff highlighted:

- Previous no-shows
- Booking lead time
- Distance to clinic
- Reminder status
- Potential interactions between these variables

These findings can support Data Science in deciding which variables and relationships should be considered during future no-show modelling.

## Limitations

- The analysis identifies associations and does not establish causation.
- Some combinations contain small numbers of patients and should therefore be interpreted cautiously.
- Distance and waiting-time fields contain missing values.
- Reminder channel differences may reflect underlying patient or operational differences.
- Further statistical and predictive modelling is required to assess predictive strength.

## Tools Used

- Microsoft Excel
- Power Query
- Power BI
- DAX
- Data Analysis
- Data Visualisation

## Project Progression

**Week 5:** Identify and visualise appointment attendance patterns  
↓  
**Week 6:** Investigate relationships and validate key findings  
↓  
**Data Science Integration:** Provide analytical findings for modelling decisions  
↓  
**Week 7:** Predictive modelling and further testing

## Outcome

Week 6 moved the HealthConnect project beyond descriptive analysis by examining how key attendance-risk factors interact.

The analysis provides a stronger evidence base for targeted attendance-support strategies and future predictive modelling.
