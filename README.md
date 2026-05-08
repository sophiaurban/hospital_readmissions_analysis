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
*1. All 6 conditions tracked by the CMS data exceeded the expected readmissions threshold ratio of 1.0. Indicates a systemic challenge in readmissions across hospitals in the U.S.
*2. Hip/Knee replacements were found to be the highest risk condition for readmission despite these procedures being elective and planned. This finding suggests possible gaps in post-discharge care rather then complexity of the condition itself
