# HAZOP Risk Analysis

HAZOP risk analysis and interactive dashboard to identify high-risk areas, recurring causes, and safety action priorities using Excel and Power Query.

![Dashboard Preview](loan_default_and_credit_risk_analysis_dashboard_screenshoot.png)

## Objective

The objective of this project is to analyze HAZOP risk data, identify the areas with higher risk exposure, understand recurring causes, and track the progress and ownership of safety actions.

## Dataset

HAZOP Risk Analysis Dataset — used for risk assessment, data cleaning, analysis, and dashboard development.

The dataset contains HAZOP-related information such as risk scores, equipment or nodes, causes, responsible teams, and action status.

## Tools Used

* Microsoft Excel
* Power Query
* Pivot Tables
* Charts
* Excel Dashboard

## Files in this repo

* `01_HAZOP_Risk_Analysis_Uncleaned Dataset .xlsx` — raw HAZOP risk dataset
* `02_Hazop_Risk_Analysis_Dahboard.xlsx` — interactive Excel dashboard
* `03_Hazop_Risk_Analysis_Key_Finding_Business_Analysis.docx` — detailed key findings and business analysis
* `04_Hazop_Risk_Analysis_Business_Report.docx` — final project report

## Methodology

* Reviewed and cleaned the raw HAZOP risk data using Power Query.
* Standardized the data to make it suitable for analysis.
* Used Pivot Tables and charts to summarize the risk data.
* Analyzed risk by equipment/node, cause, responsible team, and action status.
* Developed an interactive Excel dashboard to make the results easier to understand.
* Identified key risk areas and areas where further attention may be required.

## Key Findings

* Feed Line to R-101 and Separator V-701 have the highest risk scores, making them important areas for inspection and mitigation.
* Operations handles a larger share of the risk-weighted workload compared with Process Safety.
* Utility Failure and Operator Error are among the most recurring causes in the dataset.
* Only 25% of identified risks are marked as Closed, while Open and In Progress cases together account for 50%.
* Around 12% of entries do not have a Responsible Team assigned, indicating a potential ownership gap.
* Open and In Progress actions are increasing faster than Closed actions, showing a need for better action follow-up.

## Recommendations

* We recommend giving priority to Feed Line to R-101 and Separator V-701 during upcoming inspection and mitigation activities, as these areas show the highest risk levels.
* We suggest reviewing the current distribution of risk-related work between Operations and Process Safety, particularly for higher-risk items.
* We recommend focusing on recurring causes such as Utility Failure and Operator Error through suitable training and preventive maintenance.
* A regular review of Open and In Progress actions could help improve closure rates and keep the backlog under control.
* We recommend making the Responsible Team field mandatory so that each identified risk has a clear owner for follow-up.

## Dashboard

The interactive dashboard provides a clear view of:

* Risk by equipment/node
* Risk by cause
* Risk distribution across responsible teams
* Action status
* High-risk areas
* Overall risk priorities

## Conclusion

This project provides a structured view of HAZOP risk data and helps identify where safety attention may be required first. The analysis can support better prioritization of inspections, clearer ownership of actions, and improved follow-up of open risk items.

The dashboard and supporting analysis can be used as a simple decision-support tool for reviewing HAZOP risk information.
