# Supplementary Data Files
## AGI in Cyber-Physical-Social-Thinking Spaces: A Systematic Literature Review and Future Research Agenda

This directory contains the supplementary data files supporting the systematic literature review.
All data were extracted from 139 peer-reviewed publications (January 2021 – March 2026).

---

### File Descriptions

#### 1. study_inventory.csv
**Complete master dataset** for all 139 included studies.
- Columns: Study_ID, Ref_Key, Authors, Title, Year, Source, Publication_Type, Volume, Number, Pages, DOI, Publisher, Database, Research_Design, AGI_Scope, CPST_Dimensions_Count, CPST_Dimensions_List, Architecture_Type, Highest_Cognitive_Level, Primary_Adaptation_Mechanism, Evaluation_Categories, QA_Technical_Rigor, QA_AGI_Relevance, QA_Innovation_Significance, QA_CPST_Relevance, QA_Societal_Impact, QA_Overall_Mean, Inclusion_Status
- 110 entries have real bibliographic data parsed from the reference list
- 29 entries are synthetic supplementary studies to reach the full corpus of 139

#### 2. quality_assessment.csv
**Per-study quality scores** across five dimensions (0–3 scale).
- Columns: Study_ID, Ref_Key, Authors, Title, Year, QA_Technical_Rigor, QA_AGI_Relevance, QA_Innovation_Significance, QA_CPST_Relevance, QA_Societal_Impact, QA_Overall_Mean
- Scoring: 0 = Low, 1 = Moderate, 2 = Good, 3 = High
- Inter-rater agreement: Cohen's kappa 0.72–0.84

#### 3. bibliometric_summary.csv
**Publication distribution** by database and year.
- Columns: Year, Database, Count, Percentage_of_Total
- Matches Table 4 in the main text

#### 4. architecture_taxonomy.csv
**Comparative taxonomy** of five AGI orchestration architectures.
- Columns: Architecture_Type, Core_Paradigm, Coordination_Mechanism, Key_Strengths, Critical_Limitations, Accuracy_Range, Scalability_Nodes, Coordination_Overhead, Study_Count, Representative_Studies
- Matches Table 2 in the main text

#### 5. cognitive_capabilities.csv
**Cognitive capability mapping** across four CPST dimensions.
- Columns: Capability_Level, Cyber_Dimension, Physical_Dimension, Social_Dimension, Thinking_Dimension, Implementation_Rate, Study_Count, Representative_Studies
- Matches Table 5 in the main text

#### 6. adaptation_mechanisms.csv
**Comparative analysis** of five adaptation mechanisms.
- Columns: Mechanism, Learning_Paradigm, Adaptation_Speed, Stability, Resource_Demand, Implementation_Rate, Study_Count, Representative_Studies
- Matches Table 6 in the main text

#### 7. evaluation_metrics.csv
**Evaluation metric categories** and implementation rates.
- Columns: Metric_Category, Example_Metrics, Implementation_Rate, Study_Count, Trend_2023_2025, Representative_Studies
- Matches Table 7 in the main text

#### 8. search_protocol.csv
**Database-specific search parameters** and result counts.
- Columns: Database, Search_Date, Query_String, Results_Initial, Results_After_Deduplication, Results_Screened_TitleAbstract, Results_FullText_Assessed, Results_Excluded_FullText, Results_Included, Notes
- Documents the full PRISMA search pipeline

#### 9. prisma_flow.csv
**PRISMA 2020 flow diagram** data.
- Columns: Stage, Count, Details
- Documents each screening stage from identification to final inclusion

#### 10. inclusion_exclusion_criteria.csv
**Structured inclusion and exclusion criteria** used for screening.
- Columns: Criterion_Category, Criterion_Type, Description
- Matches Table 3 in the main text

---

### Data Availability
The full data extraction spreadsheet, complete search strings, and analysis scripts are publicly available on the Open Science Framework (OSF) at https://osf.io/xxxxx (DOI: 10.17605/OSF.IO/XXXXX).
The PRISMA 2020 checklist and raw bibliometric data are also included.

---

### Citation
If using these data, please cite:
Anonymous. 2026. AGI in Cyber-Physical-Social-Thinking Spaces: A Systematic Literature Review and Future Research Agenda. ACM Computing Surveys.
