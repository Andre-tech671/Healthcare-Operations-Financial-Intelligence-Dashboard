# Healthcare Operations: Business Intelligence & Interactive Dashboard

**AnalystLab Africa Experience Lab — Week 3 Project**  
**Project Title:** Healthcare Operations & Financial Intelligence Dashboard  
**Client / Domain:** Healthcare Operations & Provider Services  
**Analyst:** Andre Philip Nyanjahia  

---

## 📖 Project Overview
This project focuses on transforming complex healthcare operational and financial data into structured, actionable insights using Business Intelligence (BI) principles and data modeling. The objective was to build an executive widescreen dashboard that empowers hospital administration, operational leads, and financial directors to monitor patient volume trends, inpatient bed utilization, claim cost variations, and uncompensated care exposure.

---

## 🎯 Business Objectives
- **Centralize Data:** Consolidate multi-source healthcare relational entities (`encounters`, `patients`, `payers`, `organizations`, `procedures`) into a unified star schema model.
- **Isolate Logic:** Implement a dedicated `_Measures` table for robust governance and clean DAX formula management.
- **Operational Visibility:** Shift from reactive reporting to proactive patient flow and financial exposure monitoring.
- **Drill-Down Granularity:** Allow leadership to analyze volume from longitudinal macro-trends down to specific payer coverage gaps and encounter classes.

---

## 📊 Key Performance Indicators (KPIs)
Extracted from the interactive Power BI dashboard:
- **Total Encounters:** 27,891 (Total volume of patient visits across all operational facilities)
- **Average Claim Cost:** $3,640 (Mean financial cost per patient encounter)
- **Pct Encounters Over 24 Hours:** Dynamic % (Tracks inpatient extended stays and bed utilization rates)
- **Pct Zero Coverage:** 48.71% (Quantifies uncompensated care, self-pay, and uninsured exposure)

---

## 🖥️ Dashboard Preview & Features
- **Dynamic Slicers:** Filter instantly by `ENCOUNTERCLASS` (ambulatory, emergency, inpatient, urgentcare, wellness) and third-party `payers[NAME]`.
- **Top-Level KPI Cards:** High-level summary metrics displaying volume, average costs, and uninsured exposure percentages at a glance.
- **Longitudinal Trend Analysis:** Line charts mapping multi-year patient encounter velocities.
- **Financial Exposure Mapping:** Comparative visualization tracking total claim costs against active payer coverage limits.

---

## 🔍 Three Key Findings
1. **High Volume in Ambulatory/Outpatient vs. Cost Concentration in Inpatient:** Ambulatory and outpatient visits represent the vast majority of patient volume and throughput, whereas inpatient admissions—though lower in volume—drive disproportionately higher average claim costs and resource demands.
2. **Severe Uncompensated Care Exposure (48.71% Zero Coverage):** Nearly half of all recorded encounters exhibit zero payer coverage, exposing the healthcare provider to substantial bad-debt risks and uncompensated care burdens if front-end eligibility screening is absent.
3. **Payer-Specific Reimbursement Disparities:** Significant variations exist across third-party commercial and public payers when comparing total billed claim amounts against settled payer coverage, highlighting potential revenue leakage.

---

## 💡 Three Business Recommendations (Task 5)
1. **Implement Advance Financial Screening & Pre-Registration:** Deploy automated front-desk pre-registration screening workflows to identify uninsured patients early and proactively connect them with public aid or internal financial assistance programs, mitigating the 48.71% zero-coverage exposure.
2. **Establish Dedicated Outpatient Fast-Track Pathways:** Reorganize facility triage protocols to divert low-acuity walk-in encounters into dedicated ambulatory fast-track lanes, reducing emergency department congestion and lowering minor treatment costs.
3. **Conduct a Payer-Specific Contract and Reimbursement Audit:** Initiate a formal audit comparing contracted rate schedules against actual settled claim reimbursements from third-party payers to recover leakage from under-compensating agreements.

---

## ⚠️ Risks & 🚀 Opportunities
- **Risk Identified (Uncompensated Care Leakage):** High volume of zero-coverage encounters creates severe cash flow compression and bad-debt write-off risks if financial clearance is performed post-service.
- **Opportunity Identified (Optimized Facility Utilization):** Diverting low-acuity cases away from acute emergency wards frees up bed capacity and clinical staff for high-cost inpatient care, directly improving operating margins.

---

## 🛠️ Tools & Technologies Used
- **Power BI Desktop:** Star schema data modeling, advanced DAX measures, custom formatting, and executive widescreen dashboard layout (1280x720).
- **Power Query:** Data transformation, handling missing timestamps, and relational table merging.
- **Microsoft Word / Google Docs:** Executive summary writing, data-quality assessment, and Task 5 business recommendations.

---

## 📂 Repository Navigation
- `/dashboard` — Contains high-resolution screenshots and the working Power BI `.pbix` file.
- `/reports` — Contains the Executive Summary and structured BI documentation.

---

## 👨‍💻 Connect With Me
- **LinkedIn:** [Andre Philip Nyanjahia](https://www.linkedin.com/in/andre-nyanjahia-ab664228a)

*This project was completed as part of the AnalystLab Africa Experience Lab Internship Programme.*