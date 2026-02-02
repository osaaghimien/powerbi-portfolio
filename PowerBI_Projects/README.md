
# Hospital Readmission Analytics
## Overview
Hospital readmissions remain a major operational and financial challenge for healthcare systems, with avoidable 30-day readmissions driving increased costs, resource strain, and patient risk. This project analyzes hospital encounter data to identify patterns in readmission risk, cost exposure, and high-risk patient segments.

Using Power BI, the analysis translates demographic, clinical, and utilization data into actionable insights that support targeted intervention strategies. The outcome is an executive-ready analytics solution that enables hospital stakeholders to prioritize high-impact populations, evaluate financial trade-offs, and make data-driven decisions to reduce avoidable readmissions.

## Business Problem
Despite ongoing quality improvement efforts, hospitals continue to experience elevated 30-day all-cause readmission rates, resulting in increased healthcare costs, inefficient resource utilization, and avoidable patient risk. On average, a significant portion of discharged patients return within 30 days, indicating gaps in discharge planning and post-discharge care coordination.

The primary challenge lies in the inability to consistently identify, at the point of discharge, which patients are most likely to be readmitted using existing operational and clinical data. Without early risk visibility, hospitals struggle to deploy targeted interventions effectively, leading to preventable readmissions and unnecessary financial burden.

## Business Objective
The objective of this analysis is to support hospitals in reducing avoidable 30-day readmissions by identifying high-risk patient populations and quantifying the operational and financial impact of targeted interventions.

By transforming routinely collected demographic, clinical, and utilization data into actionable insights, this project enables hospital stakeholders to make informed decisions around discharge planning, care coordination, and resource allocation. Success is measured by the ability to highlight high-impact opportunities, prioritize interventions, and estimate potential cost savings and return on investment.

## Stakeholders & Use Case
This analysis is designed to support multiple hospital stakeholders involved in quality improvement, financial oversight, and patient care coordination.

**Primary stakeholders** include hospital leadership, quality improvement teams, and care coordination managers responsible for reducing readmissions and managing cost exposure. These stakeholders use the analysis to monitor performance trends, identify high-risk patient segments, and evaluate the financial impact of intervention strategies.

**Operational users**, such as case managers and care transition teams, can leverage the insights to prioritize high-risk patients at discharge and allocate follow-up resources more effectively. By combining readmission risk, cost metrics, and demographic segmentation, the analysis supports targeted, data-driven decision-making rather than broad, reactive interventions.

## Dataset Overview
The analysis is based on de-identified hospital encounter data representing patient admissions, clinical characteristics, utilization history, and discharge outcomes. Each record corresponds to an inpatient encounter and includes an indicator of whether the patient was readmitted within 30 days of discharge.

The dataset captures information that would typically be available to hospitals during or shortly after the discharge process, including demographic attributes, length of stay, cost-related measures, and indicators used to assess readmission risk. This makes the data well-suited for evaluating both current performance and opportunities for intervention.

By reflecting real-world operational and clinical data structures, the dataset supports meaningful analysis of readmission patterns, cost exposure, and high-risk patient segments relevant to hospital decision-making.

## KPIs & Metrics
| KPI | Description | Business Purpose |
|----|------------|------------------|
| **30-Day Readmission Rate (%)** | Percentage of patients readmitted within 30 days of discharge | Primary indicator of care effectiveness and discharge quality |
| **Average Cost per Readmission** | Mean cost incurred for readmitted patients | Quantifies financial impact of avoidable readmissions |
| **Average Length of Stay (LOS)** | Average number of days patients remain hospitalized | Measures operational efficiency and resource utilization |
| **High-Risk Patient Percentage** | Proportion of patients classified as high risk for readmission | Supports targeted intervention and care prioritization |
| **Total Patients Admitted** | Total number of inpatient admissions in the reporting period | Provides baseline volume for trend and comparative analysis |
| **Year-over-Year (YoY) Change Metrics** | YoY deltas for readmission rate, cost, and risk share | Tracks performance improvement or deterioration over time |

## Analytical Approach
The analysis focused on understanding patterns and drivers of 30-day hospital readmissions through a combination of descriptive analytics, segmentation, and comparative analysis. Patient encounters were evaluated across demographic, geographic, payer, and utilization dimensions to identify populations with elevated readmission risk and disproportionate cost impact.

Readmission performance was analyzed at both aggregate and segmented levels to uncover variation across age groups, insurance types, and locations. High-risk patient proportions were examined alongside readmission rates and cost metrics to assess not only current performance, but also potential future exposure.

Comparative and trend-based analyses were used to evaluate year-over-year changes and identify areas where performance improvements or regressions were occurring. This approach enabled the translation of raw encounter data into actionable insights aligned with operational and financial decision-making.

## Key Insights

The analysis revealed that hospital readmissions are not evenly distributed across the patient population. Instead, readmission risk and cost exposure are highly concentrated within specific demographic, geographic, and payer segments, creating opportunities for targeted intervention with measurable financial impact.

---

### Case 1: Targeted Readmission Reduction Among Younger High-Risk Populations
**Objective:**  
Reduce excessive readmission costs among younger adults in high-risk states while scaling effective care models observed in lower-risk populations.

**Positive Insight:**  
African American patients insured by **Aetna** exhibit a **30-day readmission rate of 6.0%**, compared to the overall system average of **10.3%**, representing a **42% relative reduction**. This suggests that payer-specific care coordination practices or benefit structures may be contributing to more effective post-discharge outcomes within this population.

**Negative Insight:**  
Patients aged **20–39 in Oklahoma** demonstrate the **highest 30-day readmission rate at 34.8%**, which is **238% higher than the system average**. This group also incurs an **average cost per readmission of $25,000**, approximately **20% higher** than the typical $21,000 per readmission.

**Business Implication:**  
Reducing the Oklahoma 20–39 age group’s readmission rate to the system average would prevent approximately **24.5 avoidable readmissions per 100 patients**, translating to **$612,500 in potential annual savings**. Applying care coordination strategies similar to those observed in the African American Aetna population could increase total savings to **over $700,000**, yielding an estimated **ROI of 280%**, assuming a $250,000 intervention cost.

---

### Case 2: Risk Containment in Aging Populations

**Objective:**  
Reduce future readmission costs and high-risk exposure among aging populations while maintaining current recovery efficiency.

**Positive Insight:**  
Patients aged **60–79 in Michigan** show a **30-day readmission rate of 8.8%**, representing an **18.8% improvement** from the prior period and remaining well below the system average of 10.3%. This indicates that existing care plans for this population are producing favorable outcomes.

**Negative Insight:**  
Despite strong readmission performance, **55.6% of patients aged 60–79 in Michigan are classified as high risk**, reflecting a **1.8% increase**. This elevated concentration of high-risk patients poses a threat to sustaining current performance and may drive future cost escalation if not proactively managed.

**Business Implication:**  
Reducing the high-risk population by just **10%** within this segment could lower projected future readmission costs by approximately **$260,000**, based on an average cost of **$26,000 per readmission per 100 patients**. With an estimated **$30,000 investment** in predictive monitoring and follow-up care, this scenario yields an estimated **ROI of 766%**.

## Business Impact & ROI
This analysis demonstrates that hospital readmissions present a significant opportunity for **cost reduction, risk mitigation, and operational improvement** when addressed through targeted, data-driven interventions rather than broad, system-wide initiatives.

By identifying high-risk populations and quantifying their associated cost exposure, the project enables stakeholders to prioritize interventions where they are most likely to produce measurable returns. Scenario-based analysis shows that relatively modest investments in care coordination, predictive monitoring, and post-discharge follow-up can yield substantial financial benefits.

Across the evaluated use cases, targeted intervention strategies show the potential to generate **six-figure annual cost savings**, with estimated returns ranging from **280% to over 700%**, depending on the population and intervention scope. Beyond financial impact, reducing avoidable readmissions also supports improved patient outcomes, more efficient use of clinical resources, and stronger performance against quality benchmarks.

Overall, the project illustrates how analytics can move beyond reporting to directly support **ROI-driven decision-making** in healthcare operations.

## Dashboard Walkthrough
The Power BI dashboard is structured to guide users from high-level performance monitoring to detailed, action-oriented analysis.

The **top section** presents executive KPI cards summarizing total patients, 30-day readmission rate, average cost per readmission, average length of stay, and high-risk patient percentage. This view provides an immediate snapshot of overall performance and highlights whether readmissions and cost exposure are trending above or below expectations.

The **trend and distribution views** allow users to explore how readmission rates, costs, and high-risk populations vary over time and across key dimensions such as age group, insurance type, and geographic location. These visuals help stakeholders quickly identify segments where performance deviates from the system average.

The **segmentation and comparison views** focus on isolating high-impact populations. Users can compare readmission performance and cost exposure across demographic and payer segments to uncover patterns that support targeted intervention strategies.

Interactive **slicers** enable dynamic filtering by age, payer, location, and reporting period, allowing users to move seamlessly between executive-level summaries and granular operational insights. A dedicated **business case comparison view** supports evaluation of intervention scenarios by translating changes in readmission rates and risk levels into estimated financial impact and ROI.

Together, the dashboard supports informed decision-making by connecting performance monitoring, risk identification, and financial evaluation within a single, cohesive analytical experience.

## Dashboard Snapshots

<img width="1372" height="794" alt="Screenshot 2026-01-16 224426" src="https://github.com/user-attachments/assets/35cdd360-21b1-4086-b23e-cd39a3cbfb5f" />

