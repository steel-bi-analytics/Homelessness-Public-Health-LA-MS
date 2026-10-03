# Homelessness & Public Health | Louisiana & Mississippi

A multi-source business intelligence and data analytics project examining homelessness, housing capacity, demographics, public health, and community resources across six Continuum of Care (CoC) regions in Louisiana and Mississippi from 2007–2024.

The project integrates federal and state datasets into interactive and static analytical products built with Tableau, Power BI, Excel, SQL, and Python.

## Project Overview

This analysis was developed to explore:

- How homelessness changed across Louisiana and Mississippi over time
- Differences in sheltered, unsheltered, and chronic homelessness
- Demographic patterns across six selected CoC regions
- Housing capacity across Emergency Shelter, Transitional Housing, Rapid Rehousing, and Permanent Supportive Housing programs
- Public-health indicators including healthcare access, chronic disease, mental distress, opioid prescribing, naloxone availability, and overdose mortality
- Geographic differences in community resources and support services

## Dashboards & Reports

### Tableau

**Homelessness & Public Health | Louisiana & Mississippi**

Interactive executive dashboard combining homelessness, housing, demographic, geographic, and public-health context.

[View the Interactive Tableau Dashboard](https://public.tableau.com/app/profile/p.g8118/viz/HomelessnessBetweenLouisianaMississippi1/HomelessnessPublicHealthLouisianaMississippi)

[View Tableau PDF Report](Tableau_Homelessness_Public_Health_Report.pdf)

### Power BI

Seven-page analytical report covering homelessness trends, demographics, housing resources, community health indicators, local resources, methodology, and project conclusions.

[View Power BI PDF Report](PowerBI_Homelessness_Public_Health_Report.pdf)

## Key Findings

- Homelessness patterns varied substantially by year and region across the six selected CoCs.
- The 2024 Tableau view contains 2,264 overall homeless PIT observations across the selected regions.
- Uninsured adult rates showed a moderate positive association with chronic homelessness across Louisiana and Mississippi (r ≈ +0.44).
- Unsheltered homelessness remained a significant challenge across multiple regions.
- Housing capacity generally increased over time, although availability and distribution differed considerably by region.
- Public-health indicators showed meaningful differences between Louisiana and Mississippi and across the study period.
- Community resource availability varied geographically, highlighting potential differences in local access to housing and support services.

## Analytical Workflow

**Source Acquisition → Scope & Harmonization → Data Preparation → Data Modeling → Statistical Analysis → Quality Assurance**

The workflow included:

- Multi-source data collection and harmonization
- Data cleaning and standardization
- Power Query transformations
- Data modeling and DAX measures
- SQL and Python analysis
- Pearson correlation analysis
- Dashboard development in Power BI and Tableau
- Cross-checking totals, filters, calculations, and source availability

## Tools & Technologies

**Visualization:** Power BI, Tableau  
**Data Analysis:** SQL, Python  
**Data Preparation:** Excel, Power Query  
**Modeling:** DAX, relational data modeling  
**Documentation & Version Control:** GitHub

## Data Sources

Primary sources include:

- U.S. Department of Housing and Urban Development (HUD) PIT/HIC and HMIS data
- Centers for Disease Control and Prevention (CDC)
- National Center for Health Statistics (NCHS)
- BRFSS / PLACES
- U.S. Census Bureau
- Louisiana and Mississippi public-health sources

## Interpretation Notes

Multi-year homelessness totals represent sums of annual Point-in-Time snapshots and should not be interpreted as counts of unique individuals.

Measure availability varies by year. Demographic reporting expands over time, and health indicators are primarily available from 2011–2024.

Missing or unavailable values remain N/A or NULL and are not treated as zero.

Pearson correlations describe statistical association and do not establish causation.

## Portfolio Purpose

This project demonstrates an end-to-end analytics workflow: sourcing and cleaning complex public datasets, integrating multiple subject areas, validating results, performing statistical analysis, and communicating findings through interactive and executive-level business intelligence products.
