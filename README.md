# hospital_readmissions_analysis

This project is intended to analyze 18,330 hospital records within the Centers for Medicare & Medicaid Services Hospital Reduction Program dataset in order to highlight patterns in excess readmission rates across conditions, sates, and individual hospitals across the U.S.
The clinical expertise developed in my nursing practice has allowed me to utilize this analysis in order to draw conclusions that have real-world implications in care delivery

## Tools 
Python [pandas, matplotlib] - used for primary data cleaning, analysis and visualization
SQL [SQLite] - used for data querying and aggregating data at the hospital level
Google Colab - notebook environment
Tableau - interactive dashboard 

## Project Files
| File | Description |
| ---- | ----------- |
| `HospitalReadmissions.ipynb` | Analysis Notebook with code and findings |
| `state_readmissions.csv` | State level aggregated metrics for visualization |
| `hospital_readmissions.csv` | Hospital-level detail with penalty risk scores |
| `download.png` | Bar chart of average excess ratio by condition |

## Key Findings 
**1. All 6 conditions tracked by the CMS data exceeded the expected readmissions threshold ratio of 1.0. Indicates a systemic challenge in readmissions across hospitals in the U.S.
**2. Hip/Knee replacements were found to be the highest risk condition for readmission despite these procedures being elective and planned. This finding suggests possible gaps in post-discharge care rather then complexity of the condition itself.
**3. Massachusetts leads nationally in excess readmissions; when State-level analysis was conducted, Massachusetts was the worst performing state with an average ratio of 1.044. This number was largely driven by a handful of high-volume academic medical centers rather than hospitals all across the state.
**4. AdventHealth Orlando was the specific hospital with the highest penalty risk across the nation. A composite penalty risk score was calculated as a ratio of excess ratio to discharge volume. 

## Clinical Context
The CMS Excess Readmissions ratio compares a hospitals actual readmissions to what their expected readmissions were based on their patient population. A ratio over 1.0 indicates that a hospital is readmitting patients more often than predicted, triggering the potential for the hospital to receive Medicare reimbursement penalties. In my clinical experience, gaps in discharge planning, improper follow up, and lack of patient education can contribute to avoidable readmissions. 

### Data Source
[CMS Hospital Readmissions Reduction Program Dataset}(https://data.cms.gov/provider-data/dataset/9n3s-kdb3)
- available to the public, updated annually
