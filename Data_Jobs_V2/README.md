# Data Jobs Dashboard 2.0

![Data Jobs Dashboard 2.0 png](../Data_Jobs_V2/Images/Project2_Dashboard_Overview.png)

[**Interactive report (Power BI Service)**](https://app.powerbi.com/view?r=eyJrIjoiY2Y4MzQ0YzQtZDFiNi00OGI2LTk5M2ItYzNkMjZlOGI2Y2M0IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

## Introduction

Version 2.0 refines the original **multi-page dashboard** into a **single, focused analytical view**. Instead of broad exploration, this iteration prioritizes **efficiency** by consolidating the most relevant job market metrics into one page.

The dashboard presents key indicators such as **Job Count**, **Median Yearly Salary**, **Median Hourly Salary**, and **Skills per Job** within a **single analytical view**. Users can compare **salary levels across job titles** and explore **skill popularity metrics** using **dynamic filters** and **parameter-driven visuals**, including switching between **absolute job counts** and **percentage-based skill popularity**.

## Skills Demonstrated

This project builds on the first version and emphasizes more **advanced Power BI concepts** and **deliberate design decisions**:

- **Single-page dashboard design:** Consolidating all key metrics into one focused analytical view to support fast insight generation.
- **Data transformation with Power Query (ETL):** Cleaning and preparing raw job posting data for analytical use.
- **Explicit DAX measures:** Creating calculated metrics to support KPIs, comparisons, and parameter-driven visuals.
- **Analytical data modeling:** Defining table relationships and a simplified analytical model to support scalable analysis.
- **KPI cards and summary metrics:** Displaying headline indicators such as **job count**, **median salaries**, and **skills per job**.
- **Skill popularity analysis:** Using parameter switching to toggle between **job count** and **job percentage** views.
- **Salary comparison across roles:** Enabling metric toggles between **median yearly** and **median hourly salary**.
- **Interactive filtering:** Slicers for **job title** and **country**, including a **reset option** to clear all selections.

### What This Version Deliberately Omits

- **No drill-through pages**
- **No geographic visualizations**
- **No multi-page navigation**

These choices were intentional to reduce complexity and keep the analysis focused on the most actionable metrics.

## Conclusion

This second iteration demonstrates a clear shift from **broad exploration** toward **focused analytical design**. By combining a streamlined single-page layout with **explicit DAX measures** and **parameter-driven visuals**, the dashboard enables faster and more deliberate analysis of the data job market.
