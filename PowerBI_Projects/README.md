# Hospital Readmission Analytics

## 📌 Overview

Hospital readmissions represent a major operational and financial challenge for healthcare systems. This project analyzes hospital encounter data to identify patterns in 30-day readmission risk, cost exposure, and high-risk patient segments.

Using Power BI, the analysis converts demographic, clinical, and utilization data into actionable insights that support targeted intervention strategies, enabling hospital stakeholders to reduce avoidable readmissions and improve operational efficiency.

---

## 🎯 Business Problem

Hospitals continue to experience elevated 30-day all-cause readmission rates, leading to increased costs, inefficient resource utilization, and avoidable patient risk. A significant portion of discharged patients return within 30 days, indicating gaps in discharge planning and post-discharge care coordination.

The core challenge is the lack of reliable, data-driven visibility at discharge to identify which patients are most likely to be readmitted. Without early risk identification, hospitals struggle to deploy targeted interventions, resulting in preventable readmissions and unnecessary financial burden.

---

## 📊 Dataset

* **Source:** De-identified hospital inpatient encounter data
* **Size:** Encounter-level records covering admissions, discharges, and 30-day outcomes
* **Key fields:**

  * Patient demographics
  * Length of stay
  * Readmission indicator (30-day)
  * Cost metrics
  * Payer type
  * Geographic location
  * Risk classification indicators

---

## 🛠 Tools Used

* Power BI
* SQL
* DAX
* Excel

---

## 🔍 Key Analysis

* Calculated 30-day readmission rates across demographic, payer, and geographic segments
* Segmented patients by age group, insurance type, and location to identify high-risk populations
* Analyzed average cost per readmission and length of stay to quantify financial exposure
* Evaluated high-risk patient concentration to assess future readmission risk
* Performed year-over-year comparisons to identify performance improvements and regressions
* Modeled intervention scenarios to estimate cost savings and ROI

---

## 📈 Results & Insights

* Readmission risk and cost exposure are highly concentrated within specific demographic, payer, and geographic segments rather than evenly distributed across the population.
* Patients aged **20–39 in Oklahoma** exhibit a **34.8% readmission rate**, more than **2× the system average**, with higher-than-average readmission costs.
* African American patients insured by **Aetna** show a **6.0% readmission rate**, representing a **42% reduction** versus the system average, indicating effective care coordination practices.
* Patients aged **60–79 in Michigan** maintain strong readmission performance (**8.8% rate**) but show a growing concentration of high-risk classifications, posing future cost risk.
<img width="934" height="495" alt="image" src="https://github.com/user-attachments/assets/b6422176-1c2e-4175-818f-6d1b4b3629b7" /> <img width="900" height="495" alt="image" src="https://github.com/user-attachments/assets/4211da64-6ecc-4c3a-967e-b0137cb14e5a" />


Targeted interventions focused on these segments demonstrate the potential to generate **six-figure annual savings** with estimated ROI ranging from **280% to over 700%**, depending on intervention scope.
<img width="1320" height="876" alt="image" src="https://github.com/user-attachments/assets/9319fc5e-57bb-4f5b-9141-3125aa6d0612" />

---

## 📎 Deliverables
- [Power BI Dashboard (.pbix)](https://github.com/osaaghimien/powerbi-portfolio/blob/main/PowerBI_Projects/Resources/30%20Days%20Readmission%20Project%20pblix.pbix)
- [Dashboard Screenshots](https://github.com/osaaghimien/powerbi-portfolio/blob/main/PowerBI_Projects/Resources/Readmission%20Dashboard%20Overview.PNG)
- KPI Calculations and DAX Logic
- SQL Queries Used for Analysis

---

## 💡 What I Learned

* How to translate healthcare operational data into KPI-driven decision tools
* How to connect readmission risk metrics with financial impact and ROI modeling
* The importance of segmentation in identifying high-value intervention opportunities
* How executive-ready dashboards can support proactive, data-driven healthcare decisions

