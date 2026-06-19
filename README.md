# Longitudinal Study: Assessing mHealth Interventions on Healthcare Worker Resilience and Burnout

<!-- Badges for Skills used -->
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Research](https://img.shields.io/badge/Clinical_Informatics-008080?style=for-the-badge)
![Data Management](https://img.shields.io/badge/Data_Curation-FF6F61?style=for-the-badge)

## 📌 Project & Publication Overview
This repository contains the comprehensive manuscript, data architecture documentation, and analysis for the upcoming co-authored study: **"Supporting Resilience Building and Mitigating Burnout: A Pilot Study Exploring an Evidence-Based mHealth Intervention for Healthcare Workers in Brazil"** (forthcoming/in press at the **IJERPH** — *International Journal of Environmental Research and Public Health*).

### 📄 Verbatim Reference Document
* **Manuscript File:** `IJERPH Companion App_10.05.24.docx`

---

## 🔍 Abstract & Clinical Informatics Context
Burnout among healthcare workers (HCWs) is a critical global public health crisis that severely degrades individual well-being and clinical care delivery networks. This single-group, 6-month pilot study investigated the operational impact and deployment behavior of the **CommCare Companion Application© (CCA©)** — an evidence-based mHealth tool designed to deliver targeted behavior-change messages to frontline personnel working within Brazil's Unified Public Health System (SUS).
---

## 💡 Implementation Insights: Data Curation & Operational Barriers
The analysis of this longitudinal study extended beyond primary clinical outcomes, identifying critical operational barriers in digital healthcare deployment:

* [cite_start]**Technological Inequity:** The requirement for Android-compatible hardware created a significant technical barrier, highlighting the necessity of assessing device interoperability in the initial planning stages of mHealth implementation[cite: 1, 2].
* [cite_start]**Engagement & Design:** Standardized, unidirectional messaging showed moderate impacts on well-being (WHO-5 increase with $p=0.03$), but restricted long-term engagement compared to interactive or human-hybrid models[cite: 1, 2].
* [cite_start]**Scalability Challenges:** High attrition rates from baseline ($n=159$) to endline ($n=36$) suggest that digital tools without real-time feedback mechanisms may inadvertently contribute to "digital fatigue" rather than alleviate stress[cite: 1, 2].

## 📊 Dashboard: Implementation Lessons Learned
The following matrix summarizes the strategic findings from the ReConecTAR project implementation:

| Domain | Finding | Recommendation |
| :--- | :--- | :--- |
| **Infrastructure** | Android-only dependency | Implement cross-platform support (iOS/Android) |
| **UX/Engagement** | Static/Passive content | Integrate real-time feedback & IA-based personalization |
| **Methodology** | High cohort attrition | Conduct pre-deployment hardware/usability surveys |
| **Sustainability** | Short intervention window | Extend study periods beyond 6 months for impact depth |

### Key Clinical Data Points Analysed:
* **Cohort Metrics:** Managed and longitudinal tracking of baseline ($n=159$) to endline ($n=36$) participant data[cite: 1].
* **Psychometric Scale Integration:** Implemented clinical data manipulation and data curation using the **Maslach Burnout Inventory (MBI)**, the **Brief Resilience Scale (BRS)**, and the **WHO-5 Well-Being Index**[cite: 1].
* **Biostatistics Insights:** The statistical output showed a 1% increase in cohort resilience, approaching significance with a $p\text{-value} = 0.064$[cite: 1]. 

The technical evaluation concluded that while remote mHealth applications hold substantial scalability advantages for behavior modification, they must be architected in tandem with broader systemic and organizational infrastructure support to fully mitigate chronic occupational stressors[cite: 1].

---


